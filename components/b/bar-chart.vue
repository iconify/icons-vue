<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n2v1khb6k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n2v1khb6k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:bar-chart" /></template>
