<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tj8yu8b3h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2048,"height":2048};
const content = `<path class="tj8yu8b3h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-mdl2:double-chevron-up-12" /></template>
