<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<circle class="sd7h_mb2w"/><path class="wm7xv6v-m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione:flag-for-european-union" /></template>
<style>
.sd7h_mb2w {
  cx: 32px;
  cy: 32px;
  r: 30px;
  fill: var(--svg-color--2a5f9e, #2a5f9e);
}

.wm7xv6v-m {
  fill: var(--svg-color--ffce31, #ffce31);
  d: path("m32 11.8l.7 2.2H35l-1.8 1.4l.7 2.2l-1.9-1.4l-1.9 1.4l.7-2.2L29 14h2.3zm0 34l.7 2.2H35l-1.8 1.3l.7 2.3l-1.9-1.4l-1.9 1.4l.7-2.3L29 48h2.3zm8.4-2.8l.7 2.2h2.4l-1.9 1.4l.7 2.2l-1.9-1.4l-1.9 1.4l.8-2.2l-1.9-1.4h2.3zm5.8-5.8l.7 2.2h2.4l-1.9 1.4l.7 2.2l-1.9-1.4l-1.9 1.4l.8-2.2l-1.9-1.4h2.3zm2.8-8.4l.7 2.2H52l-1.9 1.4l.7 2.2l-1.8-1.4l-1.9 1.4l.7-2.2l-1.9-1.4h2.3zm-2.8-8.5l.7 2.3h2.4l-1.9 1.3l.7 2.2l-1.9-1.3l-1.9 1.3l.8-2.2l-1.9-1.3h2.3zm-5.8-5.8l.7 2.3h2.4l-1.9 1.3l.7 2.2l-1.9-1.3l-1.9 1.3l.8-2.2l-1.9-1.3h2.3zM23.6 43l-.7 2.2h-2.4l1.9 1.4l-.7 2.2l1.9-1.4l1.9 1.4l-.8-2.2l1.9-1.4h-2.3zm-5.8-5.8l-.7 2.2h-2.4l1.9 1.4l-.7 2.2l1.9-1.4l1.9 1.4l-.8-2.2l1.9-1.4h-2.3zM15 28.8l-.7 2.2H12l1.9 1.4l-.7 2.2l1.8-1.4l1.9 1.4l-.7-2.2l1.9-1.4h-2.3zm2.8-8.5l-.7 2.3h-2.4l1.9 1.3l-.7 2.2l1.9-1.3l1.9 1.3l-.8-2.2l1.9-1.3h-2.3zm5.8-5.8l-.7 2.3h-2.4l1.9 1.3l-.7 2.2l1.9-1.3l1.9 1.3l-.8-2.2l1.9-1.3h-2.3z");
}

</style>
