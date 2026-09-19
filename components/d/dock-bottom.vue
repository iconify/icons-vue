<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ut3-glbdq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ut3-glbdq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:dock-bottom" /></template>
