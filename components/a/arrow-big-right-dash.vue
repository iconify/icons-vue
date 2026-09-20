<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iyqog2bgy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iyqog2bgy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:arrow-big-right-dash" /></template>
