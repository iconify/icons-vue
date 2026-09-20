<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lmcsfcc5h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="lmcsfcc5h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:bug" /></template>
