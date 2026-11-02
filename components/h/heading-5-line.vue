<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qn-l5uixg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qn-l5uixg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:heading-5-line" /></template>
