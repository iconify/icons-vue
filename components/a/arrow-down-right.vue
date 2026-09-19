<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/ntjuo63ty.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ntjuo63ty"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons-outline:arrow-down-right" /></template>
