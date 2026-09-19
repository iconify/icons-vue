<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mlj5cibrq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="mlj5cibrq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:adobe-lightroom" /></template>
