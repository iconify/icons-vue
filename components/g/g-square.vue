<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f3t4odkol.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1792,"height":1792};
const content = `<path class="f3t4odkol"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vs:g-square" /></template>
