<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bz1n9qbid.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="bz1n9qbid"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cryptocurrency:cmm" /></template>
