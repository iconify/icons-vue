<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lyuu4fy-i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lyuu4fy-i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:diko" /></template>
