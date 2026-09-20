<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m8qywvlmz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="m8qywvlmz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:cert-manager-dark" /></template>
