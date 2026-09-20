<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i8x0qptyv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i8x0qptyv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:input-method-fill" /></template>
