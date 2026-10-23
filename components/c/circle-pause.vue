<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gdt_johva.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gdt_johva"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:circle-pause" /></template>
