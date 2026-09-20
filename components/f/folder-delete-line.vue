<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gn86ay6-p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gn86ay6-p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:folder-delete-line" /></template>
