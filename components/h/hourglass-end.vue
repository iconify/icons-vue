<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mxwj6jb0z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":21,"height":24};
const content = `<path class="mxwj6jb0z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fontisto:hourglass-end" /></template>
