<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n1t24mbdf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n1t24mbdf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:golf-hole" /></template>
