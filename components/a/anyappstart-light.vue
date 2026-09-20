<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y3s83n2ce.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="y3s83n2ce"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:anyappstart-light" /></template>
