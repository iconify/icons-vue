<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uwy029bfo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uwy029bfo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:flame-solid" /></template>
