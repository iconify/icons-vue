<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e0dlm8brv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e0dlm8brv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:compass-2-line" /></template>
