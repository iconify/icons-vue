<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rql910rds.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rql910rds"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:command-line" /></template>
