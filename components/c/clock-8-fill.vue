<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t-k-0et4g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t-k-0et4g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:clock-8-fill" /></template>
