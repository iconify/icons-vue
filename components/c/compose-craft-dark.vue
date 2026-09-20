<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m2m6gubxa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="m2m6gubxa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:compose-craft-dark" /></template>
