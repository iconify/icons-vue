<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yjv3tcbah.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="yjv3tcbah"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:logo-git" /></template>
