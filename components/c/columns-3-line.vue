<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o9w9x_kqf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o9w9x_kqf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:columns-3-line" /></template>
