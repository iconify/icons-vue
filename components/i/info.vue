<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z9jx4mbxy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":192,"height":512};
const content = `<path class="z9jx4mbxy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:info" /></template>
