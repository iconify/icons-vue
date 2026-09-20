<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dwdfsqhyo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dwdfsqhyo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:language-csharp" /></template>
