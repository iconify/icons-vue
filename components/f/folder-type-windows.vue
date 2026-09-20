<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="ai6nc3bhd"/><path class="l8y9m7bko"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vscode-icons:folder-type-windows" /></template>
<style>
.ai6nc3bhd {
  fill: var(--svg-color--558fbf, #558fbf);
  d: path("M27.9 6h-9.8l-2 4H5v17h25V6Zm.1 4h-7.8l1-2H28Z");
}

.l8y9m7bko {
  fill: var(--svg-color--0078d6, #0078d6);
  d: path("m10 12.974l8.582-1.166v8.253L10 20.109Zm8.577 8.037l.008 8.261l-8.579-1.172v-7.14Zm1.041-9.355L31 10v9.956l-11.379.089ZM31 21.089V31l-11.382-1.6l-.018-8.33Z");
}

</style>
