<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zmzlr3bpr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zmzlr3bpr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:git-branch-plus" /></template>
