<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tseo9etza.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tseo9etza"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:line-dot-bottom-vertical-filled" /></template>
