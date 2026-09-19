<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yhjsrbc8n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="yhjsrbc8n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-solid:ban" /></template>
