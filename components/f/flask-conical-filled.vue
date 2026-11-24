<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o3ou4ybge.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="o3ou4ybge"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:flask-conical-filled" /></template>
