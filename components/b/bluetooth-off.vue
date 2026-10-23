<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o62-fkvhh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o62-fkvhh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:bluetooth-off" /></template>
