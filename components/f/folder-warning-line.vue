<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aaih7sebo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="aaih7sebo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:folder-warning-line" /></template>
