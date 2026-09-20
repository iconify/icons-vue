<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o3ccoib0a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="o3ccoib0a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:braille-solid" /></template>
