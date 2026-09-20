<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jz1bfel1b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jz1bfel1b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:folder-forbid-line" /></template>
