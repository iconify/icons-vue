<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t_efqme5x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":666,"height":680};
const content = `<path class="t_efqme5x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ls:linkedin" /></template>
