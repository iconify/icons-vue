<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aqsvi1ncw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="aqsvi1ncw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:github-2-line" /></template>
