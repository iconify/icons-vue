<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jgf1dgwdn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="jgf1dgwdn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:book-reader-solid" /></template>
