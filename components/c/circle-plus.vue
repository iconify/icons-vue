<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qd_1z1b6y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2048,"height":2048};
const content = `<path class="qd_1z1b6y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-mdl2:circle-plus" /></template>
