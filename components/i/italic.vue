<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oeee4ly_n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oeee4ly_n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fe:italic" /></template>
