<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f79e7ub9n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f79e7ub9n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:figma" /></template>
