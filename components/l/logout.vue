<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rahk9_b2d.css';
import '../../css/x/xjog0ebft.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rahk9_b2d"/><path class="xjog0ebft"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="circum:logout" /></template>
