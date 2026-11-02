<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xks_7xb4g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xks_7xb4g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:headphone-off-fill" /></template>
