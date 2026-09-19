<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vqofr63ct.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path clip-rule="evenodd" class="vqofr63ct"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon-plain:linux" /></template>
