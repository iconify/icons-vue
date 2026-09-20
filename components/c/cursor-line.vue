<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n53gf5b-k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n53gf5b-k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:cursor-line" /></template>
