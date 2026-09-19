<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mruly6l5j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":448,"height":512};
const content = `<path class="mruly6l5j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:font" /></template>
