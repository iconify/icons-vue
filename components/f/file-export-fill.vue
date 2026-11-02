<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/av3ar4-9j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="av3ar4-9j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:file-export-fill" /></template>
