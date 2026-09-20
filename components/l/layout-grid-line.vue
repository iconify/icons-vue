<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iqpjr_b4z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iqpjr_b4z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:layout-grid-line" /></template>
