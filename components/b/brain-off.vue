<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vmruqabkb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vmruqabkb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:brain-off" /></template>
