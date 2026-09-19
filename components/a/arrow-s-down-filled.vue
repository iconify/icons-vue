<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wb3n8obkq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wb3n8obkq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:arrow-s-down-filled" /></template>
