<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/llu2czb8q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="llu2czb8q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:arrow-down-up" /></template>
