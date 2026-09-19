<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i6r7z_bwt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="i6r7z_bwt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cib:bootstrap" /></template>
