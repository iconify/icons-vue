<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iouj3fbhr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iouj3fbhr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:box-fill" /></template>
