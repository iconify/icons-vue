<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rammq-b1n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rammq-b1n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="guidance:headphones" /></template>
