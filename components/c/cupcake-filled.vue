<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y1jo01bna.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y1jo01bna"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:cupcake-filled" /></template>
