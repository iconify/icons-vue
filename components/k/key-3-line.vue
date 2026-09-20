<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nahz22b4o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nahz22b4o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:key-3-line" /></template>
