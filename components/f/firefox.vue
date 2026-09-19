<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n1juv4bsc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n1juv4bsc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:firefox" /></template>
