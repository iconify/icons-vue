<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kkl44nb8a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="kkl44nb8a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:currency-yen" /></template>
