<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o7sh85bka.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="o7sh85bka"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cib:jekyll" /></template>
