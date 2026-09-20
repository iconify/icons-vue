<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/py_4ud_kr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="py_4ud_kr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:goodreads-g" /></template>
