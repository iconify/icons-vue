<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d0q5h4b_e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d0q5h4b_e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bxs-upvote" /></template>
