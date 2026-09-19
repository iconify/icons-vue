<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g-4ux5-sz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="g-4ux5-sz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ant-design:import-outlined" /></template>
