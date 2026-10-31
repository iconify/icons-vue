<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x3vj_5zuo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x3vj_5zuo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:bookmark-gloss" /></template>
