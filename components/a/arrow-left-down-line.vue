<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aancabc5v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="aancabc5v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:arrow-left-down-line" /></template>
