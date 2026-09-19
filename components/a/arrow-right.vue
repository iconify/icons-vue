<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mjle_n9oj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":448,"height":512};
const content = `<path class="mjle_n9oj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:arrow-right" /></template>
