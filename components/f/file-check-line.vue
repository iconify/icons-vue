<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n3hoi0mvb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n3hoi0mvb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:file-check-line" /></template>
