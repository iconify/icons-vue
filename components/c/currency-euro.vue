<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iynpo30pd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="iynpo30pd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:currency-euro" /></template>
