<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zu9hrubhr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="zu9hrubhr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:bell-fill-20" /></template>
