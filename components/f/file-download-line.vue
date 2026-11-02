<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xq_4vpbdd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xq_4vpbdd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:file-download-line" /></template>
