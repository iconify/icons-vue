<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yuaxb_far.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="yuaxb_far"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:ankh" /></template>
