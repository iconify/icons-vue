<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/isc5-ebbz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="isc5-ebbz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:chevron-circle-left-solid" /></template>
