<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iokq22b6c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":384,"height":512};
const content = `<path class="iokq22b6c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:cross" /></template>
