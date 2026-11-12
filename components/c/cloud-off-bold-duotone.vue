<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="xtpeb-edw"><path class="z3uqnlbpo"/><path class="tyft52zsu"/></g><path class="fqn-myctz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:cloud-off-bold-duotone" /></template>
<style>
.fqn-myctz {
  fill: currentColor;
  d: path("M21.4697 1.46967C21.7626 1.17678 22.2373 1.17678 22.5302 1.46967C22.8231 1.76256 22.8231 2.23732 22.5302 2.53022L2.53022 22.5302C2.23732 22.8231 1.76256 22.8231 1.46967 22.5302C1.17678 22.2373 1.17678 21.7626 1.46967 21.4697L21.4697 1.46967Z");
}

.tyft52zsu {
  d: path("M12.4766 4C14.5259 4.00013 16.3217 5.06727 17.3301 6.66895L4.4209 19.5781C2.98833 18.8927 2 17.4431 2 15.7646C2.00003 13.4256 3.91922 11.5293 6.28613 11.5293C6.57009 11.5293 6.84769 11.5563 7.11621 11.6084C6.88725 10.9976 6.76177 10.337 6.76172 9.64746C6.76172 6.52868 9.32065 4 12.4766 4Z");
}

.xtpeb-edw {
  fill: currentColor;
  opacity: var(--svg-opacity--0-5, 0.5);
}

.z3uqnlbpo {
  d: path("M18.3643 9.09082C20.4924 9.91237 21.9998 11.9586 22 14.3525C22 17.4712 19.4419 19.9998 16.2861 20H7.45605L18.3643 9.09082Z");
}

</style>
