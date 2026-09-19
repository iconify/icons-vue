<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xs2ycjb1b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2048,"height":2048};
const content = `<path class="xs2ycjb1b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-mdl2:encryption" /></template>
