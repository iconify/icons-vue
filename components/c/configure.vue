<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t99gmo0wz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="t99gmo0wz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ooui:configure" /></template>
