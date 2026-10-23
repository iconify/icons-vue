<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q-ie-nbmx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q-ie-nbmx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:leafy-green" /></template>
