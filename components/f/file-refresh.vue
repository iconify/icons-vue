<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/ggdhs8bmm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ggdhs8bmm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:file-refresh" /></template>
