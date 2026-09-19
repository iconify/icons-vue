<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/ldgi7turt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ldgi7turt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:brick" /></template>
