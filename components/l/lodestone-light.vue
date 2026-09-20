<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ymi50ubsd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ymi50ubsd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:lodestone-light" /></template>
