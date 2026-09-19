<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tav496pqt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="tav496pqt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cib:lets-encrypt" /></template>
