<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/za7eabcwa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="za7eabcwa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:chevrons-up-down-filled" /></template>
