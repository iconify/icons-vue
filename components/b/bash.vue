<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l8l8khb2z.css';
import '../../css/u/uuh2v9f7r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="l8l8khb2z"/><path class="uuh2v9f7r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:bash" /></template>
