<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kp4tieq8b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="kp4tieq8b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:blank-calendar-solid" /></template>
