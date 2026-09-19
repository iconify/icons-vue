<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/inps89biv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="inps89biv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon-plain:gradle" /></template>
