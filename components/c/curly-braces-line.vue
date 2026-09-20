<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ygghon35o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ygghon35o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="majesticons:curly-braces-line" /></template>
