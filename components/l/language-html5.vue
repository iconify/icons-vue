<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fer6cd8xj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fer6cd8xj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:language-html5" /></template>
