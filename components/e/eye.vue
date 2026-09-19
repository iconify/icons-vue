<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vkdhhhbns.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":472,"height":384};
const content = `<path class="vkdhhhbns"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:eye" /></template>
