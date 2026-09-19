<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/edumjhbrx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":384,"height":512};
const content = `<path class="edumjhbrx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-regular:hand-point-down" /></template>
