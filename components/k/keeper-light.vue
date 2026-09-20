<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vphf7_9kz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="vphf7_9kz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:keeper-light" /></template>
