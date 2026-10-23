<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ya-cssb-b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ya-cssb-b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:list-chevrons-down-up" /></template>
