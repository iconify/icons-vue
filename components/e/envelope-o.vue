<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d8z8v7boy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1792,"height":1408};
const content = `<path class="d8z8v7boy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa:envelope-o" /></template>
