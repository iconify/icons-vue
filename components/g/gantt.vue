<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tr2i9yi8b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1792,"height":1472};
const content = `<path class="tr2i9yi8b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vs:gantt" /></template>
