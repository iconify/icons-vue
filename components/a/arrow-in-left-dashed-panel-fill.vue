<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cn7d8btfu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cn7d8btfu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:arrow-in-left-dashed-panel-fill" /></template>
