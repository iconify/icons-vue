<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b9gkzib-q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b9gkzib-q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bxs-adjust" /></template>
