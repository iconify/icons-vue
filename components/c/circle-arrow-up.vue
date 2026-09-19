<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d-5pfkb2b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1200,"height":1200};
const content = `<path class="d-5pfkb2b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="el:circle-arrow-up" /></template>
