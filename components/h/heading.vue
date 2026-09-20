<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sr9t3tb3q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sr9t3tb3q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:heading" /></template>
