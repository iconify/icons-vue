<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mj81mac8p.css';
import '../../css/b/b0-g4tear.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="mj81mac8p"/><path class="b0-g4tear"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:group-access" /></template>
