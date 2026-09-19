<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a7grmv2fs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":432,"height":432};
const content = `<path class="a7grmv2fs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:loupe" /></template>
