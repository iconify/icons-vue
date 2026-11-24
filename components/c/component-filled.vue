<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/quw2mcr3e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="quw2mcr3e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:component-filled" /></template>
