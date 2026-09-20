<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x42f5accj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":25,"height":24};
const content = `<path class="x42f5accj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:expand-arrow-1" /></template>
