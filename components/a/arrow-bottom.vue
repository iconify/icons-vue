<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ed-1j8bav.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="ed-1j8bav"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bytesize:arrow-bottom" /></template>
