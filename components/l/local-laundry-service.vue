<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/buhwby_ug.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":344,"height":432};
const content = `<path class="buhwby_ug"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:local-laundry-service" /></template>
