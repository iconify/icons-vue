<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/do16onk9p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="do16onk9p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:check-2-fill" /></template>
