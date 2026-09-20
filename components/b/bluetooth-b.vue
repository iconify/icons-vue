<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vvfl5p4bi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="vvfl5p4bi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:bluetooth-b" /></template>
