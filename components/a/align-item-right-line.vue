<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kaxq7qbww.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kaxq7qbww"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:align-item-right-line" /></template>
