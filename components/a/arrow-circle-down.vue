<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/ts-x918ig.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="ts-x918ig"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:arrow-circle-down" /></template>
