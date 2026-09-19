<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tjc6tp_vo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tjc6tp_vo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ci:instagram" /></template>
