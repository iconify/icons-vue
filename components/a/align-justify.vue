<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pwdjpg6hj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pwdjpg6hj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uis:align-justify" /></template>
