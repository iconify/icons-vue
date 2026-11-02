<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q9s_kubnh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q9s_kubnh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:key-2-line" /></template>
