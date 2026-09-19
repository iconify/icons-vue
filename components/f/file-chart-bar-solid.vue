<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sq9ao7byp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="sq9ao7byp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flowbite:file-chart-bar-solid" /></template>
