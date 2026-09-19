<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/idcd7i-ig.css';
import '../../css/o/o3-2211gr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="idcd7i-ig"/><path class="o3-2211gr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:character-fraction" /></template>
