<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jb6fw3bhp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="jb6fw3bhp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconamoon:expressionless-face-fill" /></template>
