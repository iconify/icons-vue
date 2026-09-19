<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/ngy-kfbvu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ngy-kfbvu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bx-calendar-alt" /></template>
