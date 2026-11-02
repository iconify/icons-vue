<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y1sk-pb3p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y1sk-pb3p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:banknote-x-line" /></template>
