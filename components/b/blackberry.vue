<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z5gky4bwy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="z5gky4bwy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cib:blackberry" /></template>
