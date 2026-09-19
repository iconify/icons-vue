<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/euhz4we2b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="euhz4we2b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="circum:grid-2-v" /></template>
