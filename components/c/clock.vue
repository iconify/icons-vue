<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yh4_34evi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="yh4_34evi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="oi:clock" /></template>
