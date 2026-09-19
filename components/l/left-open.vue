<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rny4j3b8l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":654,"height":1000};
const content = `<path class="rny4j3b8l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="websymbol:left-open" /></template>
