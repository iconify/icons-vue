<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="tj_oq_bei"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:el-pais" /></template>
<style>
.tj_oq_bei {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M5.5 38.448h3.787c2.082.035 2.34-2.098 2.27-2.792v-23.67c0-.676-.057-2.454-2.418-2.454H5.5v-4h37v14.517h-4.135c0-6.309-2.557-10.465-7.283-10.505H19.509v11.7h3.43c2.326 0 4.462-1.497 4.375-6.964h4.099v18.64h-4.075c.122-8.121-3.966-7.627-4.92-7.645h-2.934v13.12h12.1c1.944-.105 6.86-1.562 6.86-11.524H42.5v15.597h-37z");
}

</style>
