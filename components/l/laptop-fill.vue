<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k-sh2tsju.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k-sh2tsju"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:laptop-fill" /></template>
