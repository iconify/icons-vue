<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b8n1_cneq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b8n1_cneq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconamoon:calendar-add-light" /></template>
