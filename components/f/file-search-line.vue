<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aje5j-b_n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="aje5j-b_n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:file-search-line" /></template>
