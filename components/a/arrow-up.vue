<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w29qddbpp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w29qddbpp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="majesticons:arrow-up" /></template>
