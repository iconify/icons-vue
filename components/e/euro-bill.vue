<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pu6q1ctkb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":448};
const content = `<path class="pu6q1ctkb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ps:euro-bill" /></template>
