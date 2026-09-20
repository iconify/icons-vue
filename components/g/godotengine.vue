<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s80gwi9yn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s80gwi9yn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:godotengine" /></template>
