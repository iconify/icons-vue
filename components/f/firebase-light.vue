<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sdhj22bof.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="sdhj22bof"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:firebase-light" /></template>
