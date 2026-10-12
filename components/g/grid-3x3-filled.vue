<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sxmijccds.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sxmijccds"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:grid-3x3-filled" /></template>
