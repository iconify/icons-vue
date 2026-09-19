<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mvjt2gvvm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mvjt2gvvm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="guidance:24-hours" /></template>
