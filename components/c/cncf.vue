<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/te9h1vb4r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="te9h1vb4r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:cncf" /></template>
