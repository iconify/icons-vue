<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":146};
const content = `<path class="a2qdbt_-g"/><path class="k11hisbro"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="logos:losant" /></template>
<style>
.a2qdbt_-g {
  fill: var(--svg-color--ff495c, #ff495c);
  d: path("m181.929 35.112l.372-.747l-.123-33.428l-.249-.937L72.758 111.177l-.7.926v32.1l.628 1.354z");
}

.k11hisbro {
  fill: var(--svg-color--284fff, #284fff);
  d: path("M181.908 0v35.133l38.784 38.016l-37.632 38.009L72.576.485L0 73.149l72.697 72.394l.034-34.392l-37.996-38.009l38.023-38.016l110.679 110.679l72.314-72.906z");
}

</style>
