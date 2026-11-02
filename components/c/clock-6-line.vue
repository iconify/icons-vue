<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kqkph08dj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kqkph08dj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:clock-6-line" /></template>
