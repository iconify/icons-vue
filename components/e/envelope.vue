<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="yi3yvqy5j"/><path class="kfnhiowqr"/><path class="b1j5wmbpg"/><path class="de2bz6blf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="twemoji:envelope" /></template>
<style>
.b1j5wmbpg {
  fill: var(--svg-color--99aab5, #99aab5);
  d: path("M32 5H4a4 4 0 0 0-4 4v1.03l14.528 14.496a4.88 4.88 0 0 0 6.884 0L36 10.009V9a4 4 0 0 0-4-4");
}

.de2bz6blf {
  fill: var(--svg-color--e1e8ed, #e1e8ed);
  d: path("M32 5H4A3.99 3.99 0 0 0 .405 7.275l14.766 14.767a4 4 0 0 0 5.657 0L35.595 7.275A3.99 3.99 0 0 0 32 5");
}

.kfnhiowqr {
  fill: var(--svg-color--99aab5, #99aab5);
  d: path("M11.95 17.636L.637 28.949c-.027.028-.037.063-.06.091c.34.57.814 1.043 1.384 1.384c.029-.023.063-.033.09-.06L13.365 19.05a1 1 0 0 0-1.415-1.414M35.423 29.04c-.021-.028-.033-.063-.06-.09L24.051 17.636a1 1 0 1 0-1.415 1.414l11.313 11.314c.026.026.062.037.09.06a4 4 0 0 0 1.384-1.384");
}

.yi3yvqy5j {
  fill: var(--svg-color--ccd6dd, #ccd6dd);
  d: path("M36 27a4 4 0 0 1-4 4H4a4 4 0 0 1-4-4V9a4 4 0 0 1 4-4h28a4 4 0 0 1 4 4z");
}

</style>
