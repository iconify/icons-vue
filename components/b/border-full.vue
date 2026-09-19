<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ewuhn0xab.css';
import '../../css/t/t2g-9euft.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="ewuhn0xab"/><path class="t2g-9euft"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:border-full" /></template>
