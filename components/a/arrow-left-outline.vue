<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/ki9hr6bmo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ki9hr6bmo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="eva:arrow-left-outline" /></template>
