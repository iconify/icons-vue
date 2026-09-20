<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u-9pnabwd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u-9pnabwd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:champagne-line" /></template>
