<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eepy7r-9b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2048,"height":2048};
const content = `<path class="eepy7r-9b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-mdl2:checkbox-indeterminate" /></template>
