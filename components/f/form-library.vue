<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yd5keqb7e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2048,"height":2048};
const content = `<path class="yd5keqb7e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-mdl2:form-library" /></template>
