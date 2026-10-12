<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sozdzcb0a.css';
import '../../css/v/vvjesyy_r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sozdzcb0a"/><path class="vvjesyy_r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:chart-column-big-filled" /></template>
