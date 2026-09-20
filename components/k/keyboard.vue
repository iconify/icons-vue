<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r1i1z-bbu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="r1i1z-bbu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:keyboard" /></template>
