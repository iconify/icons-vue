<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zp6b1ub2q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zp6b1ub2q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:list-ordered" /></template>
