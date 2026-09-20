<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tr56_nh0q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tr56_nh0q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:border-radius-fill" /></template>
