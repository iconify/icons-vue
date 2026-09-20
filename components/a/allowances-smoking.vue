<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/ru6anvrvd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ru6anvrvd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-freehand:allowances-smoking" /></template>
