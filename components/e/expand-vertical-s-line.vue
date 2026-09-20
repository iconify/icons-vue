<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h6se2ob5f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h6se2ob5f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:expand-vertical-s-line" /></template>
