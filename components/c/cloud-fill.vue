<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m9kx4f5-b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="m9kx4f5-b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconamoon:cloud-fill" /></template>
