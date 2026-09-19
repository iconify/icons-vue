<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ickf4xswo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":24};
const content = `<path class="ickf4xswo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fontisto:italic" /></template>
