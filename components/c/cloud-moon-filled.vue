<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ufep9qyxh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ufep9qyxh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:cloud-moon-filled" /></template>
