<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kbtikxbom.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="kbtikxbom"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:list-ordered-20-bold" /></template>
