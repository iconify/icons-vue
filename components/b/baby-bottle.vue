<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="m6n_ytles"/><path class="r9jn8lbdp"/><path class="ad__hnpne"/><path class="d6emm0bbf"/><path class="la_tsubev"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione:baby-bottle" /></template>
<style>
.ad__hnpne {
  fill: var(--svg-color--fff, #fff);
  d: path("M56.5 40.1c1 1 1 2.7 0 3.7L43.9 56.5c-1 1-2.7 1-3.7 0L21.8 38.2h32.8z");
}

.d6emm0bbf {
  fill: var(--svg-color--2090bc, #2090bc);
  d: path("m16.444 32.819l6.364-6.364l1.697 1.697l-6.364 6.364zm4.499 4.5l6.364-6.364l1.697 1.697l-6.364 6.364zm4.501 4.501l6.363-6.366l1.697 1.697l-6.363 6.365zm4.5 4.498l6.365-6.363l1.697 1.697l-6.365 6.363zm4.505 4.505l6.364-6.364l1.697 1.697l-6.364 6.364zm4.501 4.5l6.364-6.364l1.697 1.697l-6.365 6.364zM6.7 25.4c-1.5-1.5-.4-2.9 1.1-4.4L20.9 7.8c1.5-1.5 2.9-2.6 4.4-1.1l3.4 3.4c1.5 1.5.4 2.9-1.1 4.4L14.5 27.6c-1.5 1.5-2.9 2.6-4.4 1.1z");
}

.la_tsubev {
  fill: var(--svg-color--095972, #095972);
  d: path("m6.752 23.452l.778-.778l5.236 5.23l-.778.778zM22.948 7.247l.778-.778l5.232 5.232l-.778.778zm-2.698 2.7l.777-.777l5.233 5.232l-.778.778zm-2.697 2.699l.778-.778l5.23 5.236l-.779.778zm-2.703 2.701l.778-.778l5.233 5.233l-.778.778zm-2.696 2.701l.779-.778l5.23 5.236l-.779.778zm-2.703 2.699l.778-.778l5.232 5.233l-.777.778z");
}

.m6n_ytles {
  fill: var(--svg-color--ffe62e, #ffe62e);
  d: path("M12.9 8.4c-.6-.1-1.5-1.8-3.9-4.1c-2.8-2.9-4.8-2.7-6.1-1.4S1.4 6.2 4.3 9c2.4 2.4 4 3.2 4.1 3.9c.5 3.7-1.9 7.1-.4 8.5L21.4 8c-1.4-1.5-4.8.9-8.5.4");
}

.r9jn8lbdp {
  fill: var(--svg-color--b4d7ee, #b4d7ee);
  d: path("M61 39.6c1.4 1.4 1.4 3.5 0 4.9L44.5 61c-1.4 1.4-3.5 1.4-4.9 0L12.8 34.2c-1.4-1.4-1.4-3.5 0-4.9l16.5-16.5c1.4-1.4 3.5-1.4 4.9 0z");
}

</style>
