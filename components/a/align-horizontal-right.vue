<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sx2hn-xxl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2048,"height":2048};
const content = `<path class="sx2hn-xxl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-mdl2:align-horizontal-right" /></template>
