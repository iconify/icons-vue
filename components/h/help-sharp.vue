<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fuyntrele.css';
import '../../css/y/y8ocdrfcn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="fuyntrele"/><rect class="y8ocdrfcn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="famicons:help-sharp" /></template>
