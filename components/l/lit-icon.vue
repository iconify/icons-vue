<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":320};
const content = `<path class="lurbt5era"/><path class="layi-mb4r"/><path class="ks9c86i1m"/><path class="cwafcrynf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="logos:lit-icon" /></template>
<style>
.cwafcrynf {
  fill: var(--svg-color--0ff, #0ff);
  d: path("M64 320V192l64 64z");
}

.ks9c86i1m {
  fill: var(--svg-color--324fff, #324fff);
  d: path("M64 192V64l64-64v128zm128 128V192l64-64v128zM0 256V128l64 64z");
}

.layi-mb4r {
  fill: var(--svg-color--283198, #283198);
  d: path("M128 256V128l64-64v128zM0 256l64 64l9.202-60.602L64 192l-37.542 23.71z");
}

.lurbt5era {
  fill: var(--svg-color--00e8ff, #00e8ff);
  d: path("m64 192l25.926-44.727l38.233-19.114l63.974 63.974l10.833 61.754L192 320l-64-64l-38.074-25.615z");
}

</style>
