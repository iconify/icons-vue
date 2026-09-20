<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dilgw4etg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="dilgw4etg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:bedside-table-4-outline" /></template>
