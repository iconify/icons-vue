<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ojqjc3bhk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ojqjc3bhk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:cloud-check-round" /></template>
