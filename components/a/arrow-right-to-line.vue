<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/alaq-znzj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="alaq-znzj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:arrow-right-to-line" /></template>
