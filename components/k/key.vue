<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nt591tbyz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nt591tbyz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:key" /></template>
