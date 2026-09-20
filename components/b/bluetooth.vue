<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gz7llccqe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gz7llccqe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="majesticons:bluetooth" /></template>
