<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vrd258wwo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="vrd258wwo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="picon:dice5" /></template>
