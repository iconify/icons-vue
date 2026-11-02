<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bbu34-6ve.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bbu34-6ve"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:full-moon-fill" /></template>
