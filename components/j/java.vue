<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rrvu35b3m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="rrvu35b3m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="picon:java" /></template>
