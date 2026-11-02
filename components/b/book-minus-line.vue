<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/et9d3ccid.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="et9d3ccid"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:book-minus-line" /></template>
