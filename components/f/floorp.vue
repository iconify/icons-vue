<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i4z5m5b8m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i4z5m5b8m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:floorp" /></template>
