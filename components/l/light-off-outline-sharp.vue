<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vtiavv4mp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:light-off-outline-sharp" /></template>
<style>
.vtiavv4mp {
  fill: currentColor;
  d: path("M10.799 20.691q-.51-.462-.607-1.152h3.616q-.096.69-.607 1.152T12 21.154t-1.201-.463M12 4q-1.12 0-2.124.426t-1.73 1.14l-.719-.708q.986-.912 2.116-1.385T12 3q2.721 0 4.61 1.89T18.5 9.5q0 1.506-.538 2.605t-1.358 1.956l-.708-.707q.583-.575 1.094-1.543q.51-.967.51-2.311q0-2.3-1.6-3.9T12 4m8.162 16.43l-.714.714L13.304 15H8.558q-1.417-.929-2.238-2.356T5.5 9.5q0-.52.091-1.08q.092-.562.236-.897l-3.158-3.17l.708-.707zM8.85 14h3.454l-5.65-5.65q-.058.223-.106.546T6.5 9.5q0 1.35.613 2.525T8.85 14m6.685 2.77v1H8.5v-1z");
}

</style>
