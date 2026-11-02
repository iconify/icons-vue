<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mbr04_brj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mbr04_brj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:eyebrow-line" /></template>
