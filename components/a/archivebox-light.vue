<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fd7_0ccbm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="fd7_0ccbm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:archivebox-light" /></template>
