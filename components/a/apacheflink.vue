<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/geid27cpb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="geid27cpb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon-plain:apacheflink" /></template>
