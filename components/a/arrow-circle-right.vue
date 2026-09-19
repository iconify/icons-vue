<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c3hmnhbkl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c3hmnhbkl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ci:arrow-circle-right" /></template>
