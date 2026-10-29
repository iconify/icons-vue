<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zjd806e6t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zjd806e6t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:bluetooth" /></template>
