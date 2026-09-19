<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q_vv43bmb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="q_vv43bmb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cib:cc-visa" /></template>
