<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eddsisw-b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1536};
const content = `<path class="eddsisw-b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa:italic" /></template>
