<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a7weqqbxq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a7weqqbxq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:chart-bubble-round" /></template>
