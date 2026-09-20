<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="hmky8lban"/><path class="yk12f8l9s"/><path class="c38dgbc8f"/><path class="agd2-5bhj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="twemoji:flag-for-flag-bahamas" /></template>
<style>
.agd2-5bhj {
  fill: var(--svg-color--141414, #141414);
  d: path("M17.5 18l-6.058-4.5L1.364 6.013A3.974 3.974 0 0 0 0 9v18c0 1.194.534 2.254 1.364 2.987L11.442 22.5L17.5 18z");
}

.c38dgbc8f {
  fill: var(--svg-color--00abc9, #00ABC9);
  d: path("M32 5H4c-1.015 0-1.931.39-2.636 1.013L11.442 13.5H36V9a4 4 0 0 0-4-4z");
}

.hmky8lban {
  fill: var(--svg-color--00abc9, #00ABC9);
  d: path("M1.364 29.987A3.966 3.966 0 0 0 4 31h28a4 4 0 0 0 4-4v-4.5H11.442L1.364 29.987z");
}

.yk12f8l9s {
  fill: var(--svg-color--fae042, #FAE042);
  d: path("M17.5 18l-6.058 4.5H36v-9H11.442z");
}

</style>
