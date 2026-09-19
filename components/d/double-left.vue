<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/ny2vtvbul.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="ny2vtvbul"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icons8:double-left" /></template>
