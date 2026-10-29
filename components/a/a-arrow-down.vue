<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o8pdc8gsj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o8pdc8gsj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:a-arrow-down" /></template>
