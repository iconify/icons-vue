<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/ti3devbrs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ti3devbrs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:group-3-fill" /></template>
