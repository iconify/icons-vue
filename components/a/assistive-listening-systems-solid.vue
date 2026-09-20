<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vhq96o62y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="vhq96o62y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:assistive-listening-systems-solid" /></template>
