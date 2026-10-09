<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uzzrkrbqw.css';
import '../../css/y/ya12bvd4o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="uzzrkrbqw"/><path class="ya12bvd4o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:mail-open-20-bold" /></template>
