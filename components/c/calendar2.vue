<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g3odf057e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="g3odf057e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="raphael:calendar2" /></template>
