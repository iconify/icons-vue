<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j-w-e-bse.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2048,"height":2048};
const content = `<path class="j-w-e-bse"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-mdl2:crop" /></template>
