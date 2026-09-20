<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yo4uivbsf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yo4uivbsf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:hours-line" /></template>
