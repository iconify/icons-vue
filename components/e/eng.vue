<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gwxhw2ygd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="gwxhw2ygd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cryptocurrency:eng" /></template>
