<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zggtthb1v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="zggtthb1v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:ai-gaming-spark-solid" /></template>
