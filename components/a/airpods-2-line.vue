<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uao18mj6b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uao18mj6b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:airpods-2-line" /></template>
