<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t9uckj--x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t9uckj--x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:compass-3-line" /></template>
