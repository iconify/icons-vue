<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o516ekcpi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="o516ekcpi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dashicons:buddicons-forums" /></template>
