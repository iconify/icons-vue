<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j42erew0r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j42erew0r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:arrows-up-from-line" /></template>
