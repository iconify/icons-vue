<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fq7b7ybpy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="fq7b7ybpy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:database" /></template>
