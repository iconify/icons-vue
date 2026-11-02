<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ig2zuj_ca.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ig2zuj_ca"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:ai-fill" /></template>
