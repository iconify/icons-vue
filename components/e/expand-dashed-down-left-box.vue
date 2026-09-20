<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gx_x1jbqf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gx_x1jbqf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:expand-dashed-down-left-box" /></template>
