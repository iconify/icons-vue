<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="lr65hebig"/><path class="lx3-lqbai"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione:flag-for-finland" /></template>
<style>
.lr65hebig {
  fill: var(--svg-color--f9f9f9, #f9f9f9);
  d: path("M61.1 25C58 11.8 46.1 2 32 2h-1v23zM17 6C10 10.1 4.7 16.9 2.8 25H17zM2.8 39C4.7 47.1 10 53.9 17 58V39zM31 62h1c14.2 0 26-9.8 29.2-23H31z");
}

.lx3-lqbai {
  fill: var(--svg-color--428bc1, #428bc1);
  d: path("M61.1 25H31V2c-5.1.2-9.9 1.6-14 4v19H2.8c-.5 2.2-.8 4.6-.8 7s.3 4.8.8 7H17v19c4.1 2.4 8.9 3.8 14 4V39h30.2c.5-2.2.8-4.6.8-7s-.3-4.8-.9-7");
}

</style>
