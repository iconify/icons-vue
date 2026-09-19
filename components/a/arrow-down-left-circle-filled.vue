<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q1f0oo91k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q1f0oo91k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:arrow-down-left-circle-filled" /></template>
