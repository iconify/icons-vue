<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oh5rhibls.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oh5rhibls"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:alpha-x-box" /></template>
