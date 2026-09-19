<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cwt614bbp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":384};
const content = `<path class="cwt614bbp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:chevron-up" /></template>
