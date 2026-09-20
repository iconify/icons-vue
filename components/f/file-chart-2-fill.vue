<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gz9hxmb4t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gz9hxmb4t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:file-chart-2-fill" /></template>
