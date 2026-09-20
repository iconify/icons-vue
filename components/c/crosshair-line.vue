<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cnq2l7byw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cnq2l7byw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:crosshair-line" /></template>
