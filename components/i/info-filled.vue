<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dtd7c6khm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="dtd7c6khm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:info-filled" /></template>
