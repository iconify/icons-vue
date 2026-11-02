<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rjk_lmb7q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rjk_lmb7q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:ad-rectangle-off-line" /></template>
