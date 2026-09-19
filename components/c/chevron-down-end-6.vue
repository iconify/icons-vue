<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/we-lhfbwe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2048,"height":2048};
const content = `<path class="we-lhfbwe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-mdl2:chevron-down-end-6" /></template>
