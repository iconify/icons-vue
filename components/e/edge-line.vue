<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b1umm2b-i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b1umm2b-i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:edge-line" /></template>
