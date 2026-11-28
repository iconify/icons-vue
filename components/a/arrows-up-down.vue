<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yzqp71q4e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yzqp71q4e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:arrows-up-down" /></template>
