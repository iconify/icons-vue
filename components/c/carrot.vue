<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y7jepzbng.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="y7jepzbng"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:carrot" /></template>
