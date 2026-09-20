<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cn3kvq7mr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cn3kvq7mr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:file-infor-line" /></template>
