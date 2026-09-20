<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l71mmublb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l71mmublb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si:dashboard-line" /></template>
