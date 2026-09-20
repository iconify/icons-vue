<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r4d1bab8a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r4d1bab8a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:creative-commons" /></template>
