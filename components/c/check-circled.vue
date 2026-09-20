<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ev4r-7fft.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="ev4r-7fft"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="radix-icons:check-circled" /></template>
