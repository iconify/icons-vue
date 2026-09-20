<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fe9bmcbvb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fe9bmcbvb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:cassette" /></template>
