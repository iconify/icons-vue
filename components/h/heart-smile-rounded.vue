<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wdm3ikbro"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:heart-smile-rounded" /></template>
<style>
.wdm3ikbro {
  fill: currentColor;
  d: path("M12 15q1.196 0 2.184-.651t1.485-1.741q.079-.183 0-.385t-.267-.275q-.183-.073-.382.012q-.199.086-.278.269q-.358.829-1.1 1.3Q12.897 14 12 14t-1.641-.471t-1.101-1.3q-.08-.183-.278-.268q-.2-.086-.382-.013q-.188.073-.267.275t0 .385q.498 1.09 1.485 1.741T12 15M9.81 9.81q.228-.227.228-.56t-.228-.56t-.56-.228t-.56.228q-.228.227-.228.56t.228.56t.56.228t.56-.228m5.5 0q.228-.227.228-.56t-.228-.56t-.56-.228t-.56.228q-.228.227-.228.56t.228.56t.56.228t.56-.228M12 6.64q.87-1.289 2.025-1.964T16.5 4q1.908 0 3.204 1.296T21 8.52q0 .896-.293 1.782t-1.027 1.93t-1.973 2.352t-3.132 3.075l-1.48 1.346q-.46.423-1.095.423t-1.094-.423l-1.481-1.346q-1.892-1.77-3.132-3.075T4.32 12.232q-.733-1.045-1.027-1.931T3 8.519q0-1.927 1.296-3.223T7.5 4q1.32 0 2.475.675T12 6.639");
}

</style>
