<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/edi2sub5w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="edi2sub5w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:arrow-right-bold" /></template>
