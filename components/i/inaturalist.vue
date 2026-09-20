<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z5r6_0skh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":448,"height":512};
const content = `<path class="z5r6_0skh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="academicons:inaturalist" /></template>
