<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ef5-nzb-r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="ef5-nzb-r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cryptocurrency:call" /></template>
