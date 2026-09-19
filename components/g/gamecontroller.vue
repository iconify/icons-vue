<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i29p0dbzb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="i29p0dbzb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:gamecontroller" /></template>
