<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/ro6305pnm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ro6305pnm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="famicons:clipboard" /></template>
