<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d7tsbrbsw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="d7tsbrbsw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon-plain:doctrine" /></template>
