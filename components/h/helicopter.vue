<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uj6jd7bfl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="uj6jd7bfl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:helicopter" /></template>
