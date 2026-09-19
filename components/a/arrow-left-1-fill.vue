<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qvd-g2bmr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="qvd-g2bmr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconamoon:arrow-left-1-fill" /></template>
