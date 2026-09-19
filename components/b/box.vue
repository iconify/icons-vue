<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jhwmv1zcs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<rect class="jhwmv1zcs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="akar-icons:box" /></template>
