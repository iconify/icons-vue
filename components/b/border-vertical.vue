<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b1zkx-b_q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b1zkx-b_q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:border-vertical" /></template>
