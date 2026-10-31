<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bg9xddb7q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bg9xddb7q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:git-compare-round" /></template>
