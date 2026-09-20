<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iy5hwsb7z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="iy5hwsb7z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:clipboard-remove-solid" /></template>
