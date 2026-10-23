<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iunjmcccx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iunjmcccx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:file-badge" /></template>
