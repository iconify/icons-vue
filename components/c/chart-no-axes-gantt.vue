<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lxec7rbyh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lxec7rbyh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:chart-no-axes-gantt" /></template>
