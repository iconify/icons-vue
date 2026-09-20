<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p2hgsob8n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p2hgsob8n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:book-reader" /></template>
