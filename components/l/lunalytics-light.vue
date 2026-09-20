<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pum4gmbjz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="pum4gmbjz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:lunalytics-light" /></template>
