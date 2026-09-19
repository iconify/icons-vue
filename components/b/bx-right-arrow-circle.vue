<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/ktjwxgw4q.css';
import '../../css/o/oyj3-46ua.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ktjwxgw4q"/><path class="oyj3-46ua"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bx-right-arrow-circle" /></template>
