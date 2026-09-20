<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="nfkr24opq"/><path class="jg1nbpm8h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vscode-icons:file-type-light-pnpm" /></template>
<style>
.jg1nbpm8h {
  fill: var(--svg-color--4e4e4e, #4e4e4e);
  d: path("M20.374 20.375h-8.75v-8.75h8.75Zm0 9.625h-8.75v-8.75h8.75ZM30 30h-8.749v-8.75H30Zm-19.251 0H2v-8.75h8.749Z");
}

.nfkr24opq {
  fill: var(--svg-color--f9ad00, #f9ad00);
  d: path("M30 10.75h-8.749V2H30Zm-9.626 0h-8.75V2h8.75Zm-9.625 0H2V2h8.749ZM30 20.375h-8.749v-8.75H30Z");
}

</style>
