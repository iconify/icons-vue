<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lk9hjzb6f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lk9hjzb6f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bxs-comment-dots" /></template>
