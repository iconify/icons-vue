<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nprx-pcld.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nprx-pcld"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="guidance:billing-department" /></template>
