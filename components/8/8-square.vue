<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y9uth_b_n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1792,"height":1792};
const content = `<path class="y9uth_b_n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vs:8-square" /></template>
