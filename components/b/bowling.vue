<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/erkfetblq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="erkfetblq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="picon:bowling" /></template>
