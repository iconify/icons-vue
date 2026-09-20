<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o5zf5nqcs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o5zf5nqcs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:lightbulb-on-60" /></template>
