<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kebdum4nf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kebdum4nf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="guidance:bin-person" /></template>
