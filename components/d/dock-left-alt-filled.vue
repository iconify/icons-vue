<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vtu_2e0sq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vtu_2e0sq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:dock-left-alt-filled" /></template>
