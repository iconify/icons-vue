<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/io0afsb9o.css';
import '../../css/n/np4wfjoyy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="io0afsb9o"/><path class="np4wfjoyy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:cyclist" /></template>
