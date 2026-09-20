<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/ttiz4u36y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ttiz4u36y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:card-transfer-outline" /></template>
