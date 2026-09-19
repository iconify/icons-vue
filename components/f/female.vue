<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g4b_gir2i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":339,"height":720};
const content = `<path class="g4b_gir2i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ls:female" /></template>
