<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q07vdjbfy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2048,"height":2048};
const content = `<path class="q07vdjbfy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-mdl2:double-chevron-up" /></template>
