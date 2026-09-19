<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/odhkg8blp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="odhkg8blp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cryptocurrency:gno" /></template>
