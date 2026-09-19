<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qk-1gq57y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qk-1gq57y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bxs-tree" /></template>
