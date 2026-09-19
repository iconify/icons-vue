<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p-2u-zbsl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="p-2u-zbsl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bytesize:lightning" /></template>
