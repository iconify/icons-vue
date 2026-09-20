<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h0268fbty.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="h0268fbty"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:circle-play-filled" /></template>
