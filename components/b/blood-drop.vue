<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zjh781b6k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":24};
const content = `<path class="zjh781b6k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fontisto:blood-drop" /></template>
