<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qh6i7b82a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qh6i7b82a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:birdhouse" /></template>
