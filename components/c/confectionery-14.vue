<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lnrgccqxe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="lnrgccqxe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="osmic:confectionery-14" /></template>
