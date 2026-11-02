<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q2ef0i5xy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q2ef0i5xy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:circle-small-fill" /></template>
