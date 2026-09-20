<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hxaai3bkd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hxaai3bkd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:code-xml" /></template>
