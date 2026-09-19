<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/boqn2bbhz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":384,"height":384};
const content = `<path class="boqn2bbhz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:format-clear" /></template>
