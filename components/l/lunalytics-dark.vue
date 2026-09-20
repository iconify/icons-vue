<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hfoa1mbmt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="hfoa1mbmt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:lunalytics-dark" /></template>
