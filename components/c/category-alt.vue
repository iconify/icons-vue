<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b8mk0iw6q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b8mk0iw6q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bxs:category-alt" /></template>
