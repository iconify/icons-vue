<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dvs6_dj8r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="dvs6_dj8r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cib:cashapp" /></template>
