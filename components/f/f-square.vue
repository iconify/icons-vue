<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cmpahqb1q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1792,"height":1792};
const content = `<path class="cmpahqb1q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vs:f-square" /></template>
