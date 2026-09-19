<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/ga6454bvx.css';
import '../../css/o/oj97bgbfh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ga6454bvx"/><path class="oj97bgbfh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:image-portrait" /></template>
