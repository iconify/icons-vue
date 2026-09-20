<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n3uv7ib5z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n3uv7ib5z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:lucide" /></template>
