<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ykj6llbyj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ykj6llbyj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:bread-gloss" /></template>
