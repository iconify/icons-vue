<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lcuv1qq0x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="lcuv1qq0x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:latino" /></template>
