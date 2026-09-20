<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d2xjy9bql.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d2xjy9bql"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:brush-alt" /></template>
