<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y3vuzjkvz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":384,"height":512};
const content = `<path class="y3vuzjkvz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:arrow-up-long" /></template>
