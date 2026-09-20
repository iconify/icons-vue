<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/te8lzdv-n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="te8lzdv-n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:autokitteh-dark" /></template>
