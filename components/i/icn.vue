<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k7xhl_bxk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="k7xhl_bxk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cryptocurrency:icn" /></template>
