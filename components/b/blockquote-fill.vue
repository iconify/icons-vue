<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qb8tj6b7r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qb8tj6b7r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:blockquote-fill" /></template>
