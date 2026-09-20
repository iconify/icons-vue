<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/brqr-qbnj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="brqr-qbnj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-lab:chest" /></template>
