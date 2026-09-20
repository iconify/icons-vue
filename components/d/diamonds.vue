<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qnzq_abge.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qnzq_abge"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:diamonds" /></template>
