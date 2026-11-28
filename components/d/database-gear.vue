<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/minh_dbxy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="minh_dbxy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:database-gear" /></template>
