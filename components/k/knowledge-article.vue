<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wlegls60l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2048,"height":2048};
const content = `<path class="wlegls60l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-mdl2:knowledge-article" /></template>
