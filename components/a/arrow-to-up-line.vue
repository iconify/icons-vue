<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i07plyk-c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i07plyk-c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:arrow-to-up-line" /></template>
