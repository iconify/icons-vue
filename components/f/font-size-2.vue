<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e5-vskbxy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2048,"height":2048};
const content = `<path class="e5-vskbxy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-mdl2:font-size-2" /></template>
