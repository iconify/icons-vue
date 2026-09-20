<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yi-ioabzf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yi-ioabzf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:arrow-left-line" /></template>
