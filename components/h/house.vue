<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hi1n5xsqq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="hi1n5xsqq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ep:house" /></template>
