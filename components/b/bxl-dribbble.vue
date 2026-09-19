<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aoj_7yb-y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="aoj_7yb-y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bxl-dribbble" /></template>
