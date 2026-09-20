<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h6tbj45ia.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h6tbj45ia"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:help" /></template>
