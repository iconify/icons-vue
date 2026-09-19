<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nhfpk-x5d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="nhfpk-x5d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:code-download-sharp" /></template>
