<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eupi8rb3s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="eupi8rb3s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:forward-2-fill" /></template>
