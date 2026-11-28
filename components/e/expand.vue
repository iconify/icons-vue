<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ixwptel9c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ixwptel9c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:expand" /></template>
