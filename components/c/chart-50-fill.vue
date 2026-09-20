<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d6eb6zbaw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d6eb6zbaw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mage:chart-50-fill" /></template>
