<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xrq_v6q4b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xrq_v6q4b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:blob-filled" /></template>
