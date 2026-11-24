<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dd506xbwi.css';
import '../../css/z/zjahz3ydt.css';
import '../../css/u/upgqaocvh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dd506xbwi"/><path class="zjahz3ydt"/><path class="upgqaocvh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:drone-filled" /></template>
