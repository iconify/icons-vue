<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bf38tbc0j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="bf38tbc0j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:adobe-dreamweaver-dark" /></template>
