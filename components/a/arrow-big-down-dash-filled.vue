<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aha5mabrl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="aha5mabrl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:arrow-big-down-dash-filled" /></template>
