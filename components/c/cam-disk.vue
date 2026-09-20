<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lwh5tq7ua.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="lwh5tq7ua"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:cam-disk" /></template>
