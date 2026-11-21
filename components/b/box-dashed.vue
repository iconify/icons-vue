<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n9kjshfdg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n9kjshfdg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:box-dashed" /></template>
