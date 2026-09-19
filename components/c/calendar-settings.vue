<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/za8ehjb1q.css';
import '../../css/n/n_757dk6o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="za8ehjb1q"/><path class="n_757dk6o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:calendar-settings" /></template>
