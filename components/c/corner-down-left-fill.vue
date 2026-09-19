<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i1aohj47b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24,"left":0.05,"top":0.05};
const content = `<path class="i1aohj47b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="eva:corner-down-left-fill" /></template>
