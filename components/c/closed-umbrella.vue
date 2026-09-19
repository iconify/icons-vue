<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="w6oe1bxby"/><path class="qkgzojfyp"/><path class="ip29ppj_x"/><path class="v26ok12db"/><path class="ud0itsbwd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione:closed-umbrella" /></template>
<style>
.ip29ppj_x {
  fill: var(--svg-color--ffce31, #ffce31);
  d: path("M21.6 11.1c-2.9-2.9-4.3-6.7-3.7-9.8L2.7 60l32.1-46.9c-3 3.1-9 2.2-13.2-2");
}

.qkgzojfyp {
  fill: var(--svg-color--f2b200, #f2b200);
  d: path("M36.7 26.3c-4.8-4.8-3.9-9.2-2.3-12.5L2.7 60l47-32c-3.2 1.5-8.4 2.8-13-1.7");
}

.ud0itsbwd {
  fill: var(--svg-color--3e4347, #3e4347);
  d: path("m46.8 13.7l.1.1l1.7 1.7l.3.3l6.3-6.3c1-1 3-.7 4.4.6c1.4 1.4 1.7 3.3.6 4.4c-.5.5-.4 1.5.3 2.2s1.7.8 2.2.3c2.1-2.1 1.5-6-1.3-8.7c-2.8-2.8-6.7-3.4-8.7-1.3l-6.3 6.3zM.5 62.3c.5.5 1.2.6 1.6.2l3.1-3.1c-.2-.4-.4-.8-.7-1.1s-.7-.6-1.1-.7L.3 60.7c-.4.3-.3 1.1.2 1.6m43.9-41c-.1 0-.3-.1-.4-.3l-.4-.4l1.2-1.2c-.2 1.1.1 1.9-.4 1.9");
}

.v26ok12db {
  fill: var(--svg-color--ff8736, #ff8736);
  d: path("M61.6 45c-3.1.5-6.9-.8-9.8-3.7c-4.2-4.2-5.1-10.2-2-13.3l-47 32z");
}

.w6oe1bxby {
  fill: var(--svg-color--d0d0d0, #d0d0d0);
  d: path("M35.428 25.084L46.74 13.771l1.839 1.838l-11.314 11.314z");
}

</style>
