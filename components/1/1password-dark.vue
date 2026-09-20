<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rppx1zbps.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="rppx1zbps"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:1password-dark" /></template>
