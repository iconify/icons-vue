<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w5rxtxb8n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w5rxtxb8n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flowbite:archive-arrow-down-outline" /></template>
