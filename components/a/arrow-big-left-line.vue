<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p2aad8bmm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p2aad8bmm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:arrow-big-left-line" /></template>
