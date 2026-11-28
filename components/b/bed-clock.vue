<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lo7og7_1p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lo7og7_1p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:bed-clock" /></template>
