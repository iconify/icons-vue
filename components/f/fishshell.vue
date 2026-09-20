<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fgk1wuoie.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fgk1wuoie"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:fishshell" /></template>
