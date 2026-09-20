<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f2nyl6bcz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="f2nyl6bcz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zondicons:cheveron-left" /></template>
