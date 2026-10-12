<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tfbsv3wdr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tfbsv3wdr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:fishing-rod-filled" /></template>
