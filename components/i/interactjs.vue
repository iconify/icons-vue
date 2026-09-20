<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hm9o7ixyf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hm9o7ixyf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:interactjs" /></template>
