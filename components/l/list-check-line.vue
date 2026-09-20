<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eowd5-4tk.css';
import '../../css/k/kc1ovsb_n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="eowd5-4tk"/><path class="kc1ovsb_n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:list-check-line" /></template>
