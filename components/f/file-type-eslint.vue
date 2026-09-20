<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="ebd87-b5b"/><path class="mqzhngbeh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vscode-icons:file-type-eslint" /></template>
<style>
.ebd87-b5b {
  fill: var(--svg-color--4b32c3, #4b32c3);
  d: path("m29.832 16.7l-6.354 10.717A1.26 1.26 0 0 1 22.36 28H9.647a1.26 1.26 0 0 1-1.118-.59l-6.356-10.7a1.26 1.26 0 0 1 0-1.272L8.527 4.676A1.34 1.34 0 0 1 9.647 4h12.709a1.34 1.34 0 0 1 1.118.678l6.354 10.786a1.2 1.2 0 0 1 0 1.238Zm-5.262 4.2v-9.614L16 6.466l-8.56 4.82V20.9L16 25.719Z");
}

.mqzhngbeh {
  fill: var(--svg-color--8080f2, #8080f2);
  d: path("m21.802 19.188l-5.747 3.235l-5.742-3.235v-6.47l5.742-3.236l5.747 3.236z");
}

</style>
