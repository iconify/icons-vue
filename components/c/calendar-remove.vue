<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/syid8lbkh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="syid8lbkh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ci:calendar-remove" /></template>
