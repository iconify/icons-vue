<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a35ioxuoh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a35ioxuoh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bxs-chevron-down-square" /></template>
