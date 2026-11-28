<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bj65s2s8q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bj65s2s8q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:coin" /></template>
