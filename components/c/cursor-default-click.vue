<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g9jmoj0eq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g9jmoj0eq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:cursor-default-click" /></template>
