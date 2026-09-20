<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="yht5rbl3q"/><path class="fbwyb94zc"/><path class="d763v41wa"/><path class="lcx6z3buz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="twemoji:flag-senegal" /></template>
<style>
.d763v41wa {
  fill: var(--svg-color--e31b23, #e31b23);
  d: path("M32 5h-8v26h8a4 4 0 0 0 4-4V9a4 4 0 0 0-4-4");
}

.fbwyb94zc {
  fill: var(--svg-color--fdef42, #fdef42);
  d: path("M12 5h12v26H12z");
}

.lcx6z3buz {
  fill: var(--svg-color--00853f, #00853f);
  d: path("M18.869 16.674L18 14l-.869 2.674H14.32l2.274 1.652L15.726 21L18 19.348L20.274 21l-.868-2.674l2.274-1.652z");
}

.yht5rbl3q {
  fill: var(--svg-color--00853f, #00853f);
  d: path("M4 5a4 4 0 0 0-4 4v18a4 4 0 0 0 4 4h8V5z");
}

</style>
