<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ops65ob5s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ops65ob5s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:braces-duo" /></template>
