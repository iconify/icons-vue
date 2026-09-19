<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nu2_-nbje.css';
import '../../css/e/e6t7vc15w.css';
import '../../css/s/sfus55blb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="nu2_-nbje"/><path class="e6t7vc15w"/><path class="sfus55blb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:location-company" /></template>
