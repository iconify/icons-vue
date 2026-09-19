<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o22-h2bof.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o22-h2bof"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons-outline:check-circle" /></template>
