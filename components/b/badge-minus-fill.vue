<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gpa6sprsd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gpa6sprsd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:badge-minus-fill" /></template>
