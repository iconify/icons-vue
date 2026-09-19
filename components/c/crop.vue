<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g2l7g6b8b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="g2l7g6b8b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:crop" /></template>
