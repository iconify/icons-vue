<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tb2keo2id.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="tb2keo2id"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:diamond-turn-right" /></template>
