<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n1olxob1y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n1olxob1y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:badge" /></template>
