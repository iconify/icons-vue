<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u77v6ab5m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="u77v6ab5m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:home-solid" /></template>
