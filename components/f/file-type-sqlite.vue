<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<defs><linearGradient id="SVGwuIXyeeC" x1="-118.318" x2="-116.751" y1="45.638" y2="45.638" gradientTransform="matrix(0 11.486 11.486 0 -510.889 1363.307)" gradientUnits="userSpaceOnUse"><stop offset="0" class="y6s4gpb0s"/><stop offset=".92" class="sp8j_vbuq"/><stop offset="1" class="sp8j_vbuq"/></linearGradient></defs><path class="j5mclebjh"/><path fill="url(#SVGwuIXyeeC)" class="s3ocb-b5b"/><path class="f_-kf4zfg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vscode-icons:file-type-sqlite" /></template>
<style>
.f_-kf4zfg {
  fill: var(--svg-color--003b57, #003b57);
  d: path("M27.29 2.608c-1.2-1.073-2.66-.642-4.1.634q-.32.286-.638.625A25.4 25.4 0 0 0 17.1 15a10 10 0 0 1 .634 1.822c.036.14.069.272.1.384c.062.265.1.437.1.437s-.022-.083-.113-.346l-.059-.17l-.038-.094c-.16-.373-.6-1.16-.8-1.5c-.167.493-.315.954-.438 1.371a12 12 0 0 1 .908 2.8s-.03-.115-.171-.515a19 19 0 0 0-.9-1.708a4 4 0 0 0-.264 1.724a6 6 0 0 1 .493 1.383c.334 1.283.566 2.846.566 2.846l.02.263a26 26 0 0 0 .065 3.205a11.4 11.4 0 0 0 .584 3.1l.18-.1a13.9 13.9 0 0 1-.478-4.628a35.3 35.3 0 0 1 1.938-9.688c2.01-5.308 4.8-9.568 7.35-11.6c-2.326 2.1-5.474 8.9-6.417 11.418a45.7 45.7 0 0 0-2.254 8A6.2 6.2 0 0 1 21.39 20s1.233-1.521 2.674-3.693a26 26 0 0 0-2.755.733c-.7.294-.889.394-.889.394a24 24 0 0 1 4.215-2.007c2.676-4.215 5.592-10.2 2.656-12.824");
}

.j5mclebjh {
  fill: var(--svg-color--0f80cc, #0f80cc);
  d: path("M23.192 3.242H5.623a2.147 2.147 0 0 0-2.141 2.141v19.376A2.147 2.147 0 0 0 5.623 26.9h11.572c-.132-5.758 1.835-16.932 5.997-23.658");
}

.s3ocb-b5b {
  d: path("M22.554 3.867H5.623a1.52 1.52 0 0 0-1.516 1.516v17.962a42 42 0 0 1 13.569-2.684a123.6 123.6 0 0 1 4.878-16.794");
}

.sp8j_vbuq {
  stop-color: var(--svg-color--0f80cc, #0f80cc);
}

.y6s4gpb0s {
  stop-color: var(--svg-color--97d9f6, #97d9f6);
}

</style>
