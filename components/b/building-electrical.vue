<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o59q0tj2u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="o59q0tj2u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:building-electrical" /></template>
