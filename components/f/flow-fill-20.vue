<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i8uofudft.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="i8uofudft"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:flow-fill-20" /></template>
