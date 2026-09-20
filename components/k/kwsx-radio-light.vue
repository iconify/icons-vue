<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hh7x7d29g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="hh7x7d29g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:kwsx-radio-light" /></template>
