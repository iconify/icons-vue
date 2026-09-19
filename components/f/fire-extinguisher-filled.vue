<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pv05icc_n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pv05icc_n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:fire-extinguisher-filled" /></template>
