<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g0m-3nbpr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g0m-3nbpr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:lucide" /></template>
