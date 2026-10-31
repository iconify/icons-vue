<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qfk9wvb1r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qfk9wvb1r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:linkedin-fill-round" /></template>
