<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/ba-9j369s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ba-9j369s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:heading-6-line" /></template>
