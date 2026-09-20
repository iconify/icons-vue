<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gvzoaacaq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gvzoaacaq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:git-merge-fill" /></template>
