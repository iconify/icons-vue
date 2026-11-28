<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fkyxbsb2b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fkyxbsb2b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:clipboard-list-plus" /></template>
