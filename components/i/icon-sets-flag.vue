<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m134ul6od.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2048,"height":2048};
const content = `<path class="m134ul6od"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-mdl2:icon-sets-flag" /></template>
