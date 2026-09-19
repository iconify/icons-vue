<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zijllk4_l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zijllk4_l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:dashed-line-circle" /></template>
