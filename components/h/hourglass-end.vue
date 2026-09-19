<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hqhyvdoxs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":384,"height":512};
const content = `<path class="hqhyvdoxs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:hourglass-end" /></template>
