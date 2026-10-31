<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bgjq24bqv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bgjq24bqv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:keyframes-fill-round" /></template>
