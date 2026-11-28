<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j_ok3bclj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j_ok3bclj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:align-vertical-space-between-solid" /></template>
