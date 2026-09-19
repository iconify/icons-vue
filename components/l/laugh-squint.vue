<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t12a6fb-c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="t12a6fb-c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-regular:laugh-squint" /></template>
