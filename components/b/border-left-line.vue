<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/idq842onv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="idq842onv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:border-left-line" /></template>
