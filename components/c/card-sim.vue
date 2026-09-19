<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/up5sddcmh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":344,"height":432};
const content = `<path class="up5sddcmh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:card-sim" /></template>
