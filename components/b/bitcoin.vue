<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u-g6nkb8l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u-g6nkb8l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:bitcoin" /></template>
