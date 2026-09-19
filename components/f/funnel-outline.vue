<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s0e9-g4hi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s0e9-g4hi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="eva:funnel-outline" /></template>
