<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="k2xyk619o"/><path class="lu28nlxny"/><path class="kq3x18pzk"/><path class="y_q__pbfm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione:bomb" /></template>
<style>
.k2xyk619o {
  fill: var(--svg-color--d3976e, #d3976e);
  d: path("M13.8 22.5C9.4 18.1 8 14.4 9.6 11.6c3.1-5.5 18-5.5 30.4-2.7l-.4 1.8C28 8.2 13.9 8.1 11.3 12.6c-1.4 2.5 1.3 6.1 3.9 8.7z");
}

.kq3x18pzk {
  fill: var(--svg-color--ed4c5c, #ed4c5c);
  d: path("M43 14v2.9c0 1.2 1.9 1.2 1.9 0V14c0-1.2-1.9-1.2-1.9 0m0-11.1v2.8c0 1.2 1.9 1.2 1.9 0V2.9c0-1.2-1.9-1.2-1.9 0m5.2 7.9h2.9c1.2 0 1.2-1.9 0-1.9h-2.9c-1.2.1-1.2 1.9 0 1.9");
}

.lu28nlxny {
  fill: var(--svg-color--ffce31, #ffce31);
  d: path("M41.2 11.3c-1 1-2 1.9-2.9 2.9c-.9.9.5 2.2 1.3 1.3c1-1 2-1.9 2.9-2.9c.9-.8-.4-2.2-1.3-1.3m5.6-2.8l2.9-2.9c.9-.9-.5-2.2-1.3-1.3l-2.9 2.9c-.9.8.4 2.1 1.3 1.3m-1.4 4.1c1 1 2 1.9 2.9 2.9c.9.9 2.2-.5 1.3-1.3c-1-1-2-1.9-2.9-2.9c-.8-.9-2.2.5-1.3 1.3m-7.1-7l2.9 2.9c.9.9 2.2-.5 1.3-1.3l-2.9-2.9c-.8-.9-2.2.5-1.3 1.3");
}

.y_q__pbfm {
  fill: var(--svg-color--3e4347, #3e4347);
  d: path("m10.7 24.2l6-5.9l3.8 3.7c3.5-2.4 7.8-3.7 12.4-3.7C45.1 18.2 55 28 55 40.1S45.1 62 32.8 62c-12.2 0-22.2-9.8-22.2-21.9c0-4.5 1.4-8.7 3.8-12.2z");
}

</style>
