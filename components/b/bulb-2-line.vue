<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g7h7tbcly.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g7h7tbcly"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:bulb-2-line" /></template>
