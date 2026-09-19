<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o-4jio4dy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="o-4jio4dy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cil:expand-left" /></template>
