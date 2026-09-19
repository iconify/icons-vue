<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eriqo0v6q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="eriqo0v6q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bxs-file" /></template>
