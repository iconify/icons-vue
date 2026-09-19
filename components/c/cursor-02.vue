<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zta7qc5xb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zta7qc5xb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:cursor-02" /></template>
