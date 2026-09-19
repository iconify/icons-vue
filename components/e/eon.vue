<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ibth7vl9w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="ibth7vl9w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cryptocurrency:eon" /></template>
