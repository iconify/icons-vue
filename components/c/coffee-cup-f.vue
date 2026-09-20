<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fa8bghbvb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24,"left":-2,"top":-6};
const content = `<path class="fa8bghbvb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="jam:coffee-cup-f" /></template>
