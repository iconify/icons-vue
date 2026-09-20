<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/obyk81pmq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="obyk81pmq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:hourglass-start" /></template>
