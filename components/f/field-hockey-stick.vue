<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n5w92nb7k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="n5w92nb7k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:field-hockey-stick" /></template>
