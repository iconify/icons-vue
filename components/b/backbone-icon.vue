<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":318};
const content = `<path class="ep0oz-bdq"/><path class="ch2-5y3oo"/><path class="gkaoe6b5d"/><path class="ho6d-lbqz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="logos:backbone-icon" /></template>
<style>
.ch2-5y3oo {
  fill: var(--svg-color--0071b5, #0071b5);
  d: path("M255.967 0v171.945L127.984 244.9v-49.592l85.619-48.807v-76.66l-85.62 48.806V72.956z");
}

.ep0oz-bdq {
  fill: var(--svg-color--002a41, #002a41);
  d: path("M0 0v171.945L127.984 244.9v-49.592l-85.62-48.807v-76.66l85.62 48.806V72.956z");
}

.gkaoe6b5d {
  fill: var(--svg-color--0071b5, #0071b5);
  d: path("M0 317.933V145.988l127.984-72.956v49.592l-85.62 48.806v72.761l85.62-48.806v49.592z");
}

.ho6d-lbqz {
  fill: var(--svg-color--002a41, #002a41);
  d: path("M255.967 317.933V145.988L127.984 73.032v49.592l85.619 48.806v72.761l-85.62-48.806v49.592z");
}

</style>
