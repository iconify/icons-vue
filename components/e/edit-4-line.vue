<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zvyv4v4qf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zvyv4v4qf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:edit-4-line" /></template>
