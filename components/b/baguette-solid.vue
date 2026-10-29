<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vboqt815i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vboqt815i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:baguette-solid" /></template>
