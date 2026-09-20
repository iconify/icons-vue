<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iax57h7ct.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="iax57h7ct"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:flightradar24-light" /></template>
