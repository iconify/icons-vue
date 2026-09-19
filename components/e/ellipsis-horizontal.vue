<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ulv-178_k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ulv-178_k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:ellipsis-horizontal" /></template>
