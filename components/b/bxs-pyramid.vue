<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eh3esxb-q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="eh3esxb-q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bxs-pyramid" /></template>
