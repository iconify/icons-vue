<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hsrzeq-ig.css';
import '../../css/u/um_le5b4k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="hsrzeq-ig"/><path class="um_le5b4k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:kubernetes-pod" /></template>
