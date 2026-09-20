<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kmtk7xb0r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kmtk7xb0r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:bookmark-line" /></template>
