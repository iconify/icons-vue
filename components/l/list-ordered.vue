<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o17jckbty.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o17jckbty"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:list-ordered" /></template>
