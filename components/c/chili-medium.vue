<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hkjjnzrxz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hkjjnzrxz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:chili-medium" /></template>
