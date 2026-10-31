<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tu50btbzx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tu50btbzx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:magnet-gloss" /></template>
