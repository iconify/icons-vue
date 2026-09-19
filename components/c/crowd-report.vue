<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zu_6g5b9q.css';
import '../../css/n/nu2_-nbje.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="zu_6g5b9q"/><path class="nu2_-nbje"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:crowd-report" /></template>
