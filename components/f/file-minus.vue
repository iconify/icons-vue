<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o9zo-34oi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o9zo-34oi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:file-minus" /></template>
