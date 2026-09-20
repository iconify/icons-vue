<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ezcpi4ljm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="ezcpi4ljm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-line-icons:earphones" /></template>
