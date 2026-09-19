<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sihxiybtl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sihxiybtl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bx-minus-front" /></template>
