<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pro9brbhy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pro9brbhy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:dish-cover-line" /></template>
