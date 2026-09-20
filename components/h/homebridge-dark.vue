<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y8j3sfweg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="y8j3sfweg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:homebridge-dark" /></template>
