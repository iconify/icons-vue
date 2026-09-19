<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c_35_czod.css';
import '../../css/e/efsylsb0d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="c_35_czod"/><path class="efsylsb0d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:chevron-down-outline" /></template>
