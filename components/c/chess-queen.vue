<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lo7khsgtq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lo7khsgtq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:chess-queen" /></template>
