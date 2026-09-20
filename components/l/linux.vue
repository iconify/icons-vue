<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sa23_2rjh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="sa23_2rjh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="picon:linux" /></template>
