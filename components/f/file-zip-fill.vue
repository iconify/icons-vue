<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q26x31bna.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q26x31bna"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:file-zip-fill" /></template>
