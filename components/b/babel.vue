<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bf8b3dbjt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="bf8b3dbjt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon-plain:babel" /></template>
