<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u2kr22bcu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u2kr22bcu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:finger-press-line" /></template>
