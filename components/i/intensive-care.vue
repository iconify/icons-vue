<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vq1py9j2j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vq1py9j2j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="guidance:intensive-care" /></template>
