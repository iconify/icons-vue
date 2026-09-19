<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oxgr81h8m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2048,"height":2048};
const content = `<path class="oxgr81h8m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-mdl2:circle-fill" /></template>
