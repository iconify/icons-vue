<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="vyd-2lboe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vscode-icons:file-type-vlt" /></template>
<style>
.vyd-2lboe {
  fill: var(--svg-color--fff, #fff);
  d: path("M25.333 3.24a4.666 4.666 0 1 1 0 9.333c-.743 0-1.506.281-1.877.924l-3.06 5.308c-.664 1.152-.359 2.594.048 3.86a4.667 4.667 0 1 1-8.888 0c.407-1.266.712-2.708.048-3.86l-3.061-5.308c-.371-.643-1.133-.924-1.876-.924a4.666 4.666 0 1 1 4.444-3.238c-.407 1.266-.713 2.707-.049 3.86l3.061 5.307c.371.644 1.134.925 1.877.925s1.506-.281 1.877-.924l3.06-5.309c.665-1.152.359-2.593-.047-3.859a4.666 4.666 0 0 1 4.443-6.095");
}

</style>
