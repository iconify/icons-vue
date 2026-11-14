<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ka4905bbd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:baseball-location" /></template>
<style>
.ka4905bbd {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M1.75 12q0-4.246 3.002-7.248T12 1.75t7.248 3.002T22.25 12q0 .487-.039.958q-.152-.177-.322-.347Q20.278 11 18 11t-3.889 1.611T12.5 16.5q0 2.619 2.461 5.342q-1.396.408-2.961.408q-4.246 0-7.248-3.002T1.75 12m15.762 10.569Q13.75 19.345 13.75 16.5q0-1.76 1.245-3.005T18 12.25t3.005 1.245T22.25 16.5q0 2.845-3.762 6.069q-.05.044-.108.078q-.057.033-.12.056q-.062.024-.128.035q-.065.012-.132.012t-.132-.012q-.066-.011-.128-.035q-.063-.023-.12-.056q-.058-.034-.108-.078M20.75 16.5q0 1.986-2.75 4.499q-2.75-2.513-2.75-4.499q0-2.75 2.75-2.75q1.139 0 1.945.805q.805.806.805 1.945M18 19.252q1.5-1.596 1.5-2.752q0-1.5-1.5-1.5t-1.5 1.5q0 1.156 1.5 2.752");
}

</style>
