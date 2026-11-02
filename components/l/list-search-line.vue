<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kzt6r2bpq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kzt6r2bpq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:list-search-line" /></template>
