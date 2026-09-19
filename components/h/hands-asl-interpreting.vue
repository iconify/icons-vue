<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/opi5-vb6h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":512};
const content = `<path class="opi5-vb6h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:hands-asl-interpreting" /></template>
