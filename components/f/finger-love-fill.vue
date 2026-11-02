<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sjy9pcclm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sjy9pcclm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:finger-love-fill" /></template>
