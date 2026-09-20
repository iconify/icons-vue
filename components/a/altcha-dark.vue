<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m9y-1ji3v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="m9y-1ji3v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:altcha-dark" /></template>
