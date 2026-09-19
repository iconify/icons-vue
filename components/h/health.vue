<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dk_-lhb-c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2048,"height":2048};
const content = `<path class="dk_-lhb-c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-mdl2:health" /></template>
