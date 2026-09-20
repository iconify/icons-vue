<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fhd5tfbso.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="fhd5tfbso"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lsicon:light-snow-filled" /></template>
