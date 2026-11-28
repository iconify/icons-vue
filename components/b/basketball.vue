<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gmi3pacbn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gmi3pacbn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:basketball" /></template>
