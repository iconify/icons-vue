<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kdi5s9ivd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":432,"height":408};
const content = `<path class="kdi5s9ivd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:card-travel" /></template>
