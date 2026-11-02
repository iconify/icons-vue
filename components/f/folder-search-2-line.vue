<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xlnfd2b4r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xlnfd2b4r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:folder-search-2-line" /></template>
