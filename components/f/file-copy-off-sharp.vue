<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="igw8dsv7b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:file-copy-off-sharp" /></template>
<style>
.igw8dsv7b {
  fill: currentColor;
  d: path("M20 17.246L7 4.112V2h8.5L20 6.5zm.654 4.823L16.584 18H7V8.416l-5.07-5.07l.708-.708l18.723 18.723zM15 7h4.154L15 2.846L19.154 7L15 2.846zM3 22V9h1v12h11v1z");
}

</style>
