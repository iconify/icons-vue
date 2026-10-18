<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/svcembh9y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="svcembh9y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:book-text" /></template>
