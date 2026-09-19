<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wbf6h660b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wbf6h660b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="basil:arrow-down-outline" /></template>
