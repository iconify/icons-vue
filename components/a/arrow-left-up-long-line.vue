<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qyflgxb0c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qyflgxb0c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:arrow-left-up-long-line" /></template>
