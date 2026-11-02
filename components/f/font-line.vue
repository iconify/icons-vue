<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t45-fcbyc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t45-fcbyc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:font-line" /></template>
