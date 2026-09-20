<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t88koabfd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t88koabfd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:arrow-up-to-line" /></template>
