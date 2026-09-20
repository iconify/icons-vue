<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jqd_v-g0b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="jqd_v-g0b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:beanie" /></template>
