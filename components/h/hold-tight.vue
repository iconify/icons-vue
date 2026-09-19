<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rq6_a9bmt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rq6_a9bmt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="guidance:hold-tight" /></template>
