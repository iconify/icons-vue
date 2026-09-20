<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gk4maq4cx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="gk4maq4cx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ooui:larger-text" /></template>
