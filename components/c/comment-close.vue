<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rrcy25pqu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rrcy25pqu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconamoon:comment-close" /></template>
