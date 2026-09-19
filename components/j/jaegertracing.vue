<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uuq4we08l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="uuq4we08l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon-plain:jaegertracing" /></template>
