<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eiw5a_xxt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="eiw5a_xxt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-brands:goodreads-g" /></template>
