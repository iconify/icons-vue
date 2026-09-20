<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mkp08up-q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="mkp08up-q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="picon:helicopter" /></template>
