<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zgy6b1-ya.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="zgy6b1-ya"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-brands:firefox-browser" /></template>
