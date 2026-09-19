<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/czbj6bb-q.css';
import '../../css/r/rioz_6b_m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="czbj6bb-q"/><path class="rioz_6b_m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:mail-reply" /></template>
