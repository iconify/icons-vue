<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/baaqp0b9y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="baaqp0b9y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:error-warning-line" /></template>
