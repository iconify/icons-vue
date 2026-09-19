<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xu6r7n82p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":448};
const content = `<path class="xu6r7n82p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ps:daft-punk" /></template>
