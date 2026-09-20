<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lwq5pdbxk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:call-end-sharp" /></template>
<style>
.lwq5pdbxk {
  fill: currentColor;
  d: path("M4.025 17L.4 13.475l1-1.025q2.175-2.225 4.963-3.337T12 8t5.625 1.113T22.6 12.45l1 1.025L19.975 17L16 14v-3.35q-.95-.3-1.95-.475T12 10t-2.05.175T8 10.65V14z");
}

</style>
