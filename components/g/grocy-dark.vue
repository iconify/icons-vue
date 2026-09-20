<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/klv4feksd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="klv4feksd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:grocy-dark" /></template>
