<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/ksjvsb74q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ksjvsb74q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:duckdb" /></template>
