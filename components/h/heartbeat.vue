<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h-_fu0bnp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1792,"height":1536};
const content = `<path class="h-_fu0bnp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa:heartbeat" /></template>
