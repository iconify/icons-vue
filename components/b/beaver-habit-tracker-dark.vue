<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r2f-szb8a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="r2f-szb8a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:beaver-habit-tracker-dark" /></template>
