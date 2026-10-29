<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e371slb9f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e371slb9f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:lamp" /></template>
