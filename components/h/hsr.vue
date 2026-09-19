<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rp4p6dprq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="rp4p6dprq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cryptocurrency:hsr" /></template>
