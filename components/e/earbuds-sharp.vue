<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vipgs5z9o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:earbuds-sharp" /></template>
<style>
.vipgs5z9o {
  fill: currentColor;
  d: path("M4.818 19.184Q3.5 17.868 3.5 16V6.046q0-1.061.748-1.804q.748-.742 1.79-.742H8.5v5h-4V16q0 1.458 1.022 2.48q1.021 1.02 2.48 1.02t2.479-1.02T11.5 16V8q0-1.868 1.316-3.184Q14.13 3.5 15.997 3.5t3.185 1.316T20.5 8v10q0 1.044-.76 1.772q-.761.728-1.786.728H15.5v-5h4V8q0-1.458-1.022-2.48q-1.021-1.02-2.48-1.02t-2.479 1.02T12.5 8v8q0 1.868-1.315 3.184Q9.869 20.5 8.002 20.5t-3.185-1.316");
}

</style>
