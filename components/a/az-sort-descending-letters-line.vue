<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kch8dlblq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kch8dlblq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:az-sort-descending-letters-line" /></template>
