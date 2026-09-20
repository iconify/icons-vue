<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/he98s6lwo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="he98s6lwo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:ladder-remix" /></template>
