<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/clusz_b3e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":26,"height":26};
const content = `<path class="clusz_b3e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:bar-chart-26" /></template>
