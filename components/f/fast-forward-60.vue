<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zugi9wbfj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zugi9wbfj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:fast-forward-60" /></template>
