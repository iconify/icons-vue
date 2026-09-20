<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t9v9lzovw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="t9v9lzovw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:chart-bar-solid" /></template>
