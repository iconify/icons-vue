<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uv8mvflwb.css';
import '../../css/j/jefef3bul.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="uv8mvflwb"/><path class="jefef3bul"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:battery-prismatic-20-bold" /></template>
