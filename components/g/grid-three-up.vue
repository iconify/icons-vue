<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f4q8hjbxf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="f4q8hjbxf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="oi:grid-three-up" /></template>
