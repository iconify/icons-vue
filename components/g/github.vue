<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t4--xkonr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="t4--xkonr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:github" /></template>
