<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vh-7cqz1c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="vh-7cqz1c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:chart-bar" /></template>
