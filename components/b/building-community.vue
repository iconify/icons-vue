<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uudlwutcj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uudlwutcj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:building-community" /></template>
