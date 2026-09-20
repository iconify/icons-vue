<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ag8rzbiiv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="ag8rzbiiv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:figma" /></template>
