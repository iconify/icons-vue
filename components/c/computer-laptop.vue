<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kxjghm4yn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="kxjghm4yn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zondicons:computer-laptop" /></template>
