<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q4_65ebcj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q4_65ebcj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="meteor-icons:expand" /></template>
