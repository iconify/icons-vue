<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f9la713um.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="f9la713um"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-solid:cookie" /></template>
