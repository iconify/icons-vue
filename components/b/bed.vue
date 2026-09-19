<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/ges_c3t5w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="ges_c3t5w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icons8:bed" /></template>
