<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<circle class="ov_j9rzim"/><path class="cdji1xfgt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione:flag-for-flag-vietnam" /></template>
<style>
.cdji1xfgt {
  fill: var(--svg-color--ffe62e, #ffe62e);
  d: path("m32 39l9.9 7l-3.7-11.4l9.8-7.4H35.8L32 16l-3.7 11.2H16l9.8 7.4L22.1 46z");
}

.ov_j9rzim {
  cx: 32px;
  cy: 32px;
  r: 30px;
  fill: var(--svg-color--f42f4c, #f42f4c);
}

</style>
