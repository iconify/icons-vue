<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d_fat9ykp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d_fat9ykp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:list-filter-solid" /></template>
