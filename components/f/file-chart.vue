<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tqd6ufbuq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tqd6ufbuq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:file-chart" /></template>
