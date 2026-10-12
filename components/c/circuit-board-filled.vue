<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fqk8or5gl.css';
import '../../css/a/a913n8goh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fqk8or5gl"/><path class="a913n8goh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:circuit-board-filled" /></template>
