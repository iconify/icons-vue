<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vyn0gmukb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="vyn0gmukb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:ignidash-dark" /></template>
