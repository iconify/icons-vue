<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aptqpabig.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":448,"height":512};
const content = `<path class="aptqpabig"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="academicons:google-scholar-square" /></template>
