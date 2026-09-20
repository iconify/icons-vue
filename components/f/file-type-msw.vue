<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<rect class="smdd-eb7a"/><path class="n0erw5b4b"/><path class="ywdfr36de"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vscode-icons:file-type-msw" /></template>
<style>
.n0erw5b4b {
  fill: var(--svg-color--7a1818, #7a1818);
  d: path("M7.58 11.96a4.3 4.3 0 0 1 1.57-2.9a4.3 4.3 0 0 1 3.15-.93a4.3 4.3 0 0 1 2.76 1.4l7.41 8.23a4.3 4.3 0 0 1 1.1 3.1a4.3 4.3 0 0 1-1.42 2.98a4.3 4.3 0 0 1-2.88 1.1H9.22a2.7 2.7 0 0 1-1.9-.8a2.7 2.7 0 0 1-.8-1.9v-.1zm4.05.16a.4.4 0 0 0-.13.25L10.6 21h8.67q.13 0 .22-.07l.03-.02a.4.4 0 0 0 .12-.25q0-.15-.1-.26l-7.41-8.24a.4.4 0 0 0-.23-.12a.4.4 0 0 0-.27.08");
}

.smdd-eb7a {
  width: 28px;
  height: 28px;
  x: 2px;
  y: 2px;
  rx: 5.25px;
}

.ywdfr36de {
  fill: var(--svg-color--ff6a33, #ff6a33);
  d: path("m9.12 7.05l13.66.02a2.7 2.7 0 0 1 1.9.79a2.7 2.7 0 0 1 .8 1.9v.1l-.02.1l-1.42 13.67a2.7 2.7 0 0 1-.98 1.82a2.7 2.7 0 0 1-3.7-.3L7.11 11.56a2.7 2.7 0 0 1-.69-1.94a2.7 2.7 0 0 1 2.7-2.56M11.9 11l8.5 9.45l.99-9.44z");
}

</style>
