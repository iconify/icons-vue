<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c1d2wgbko.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="c1d2wgbko"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:candy-cane-solid" /></template>
