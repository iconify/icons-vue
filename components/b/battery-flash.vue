<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b6yn4_bji.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":216,"height":432};
const content = `<path class="b6yn4_bji"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:battery-flash" /></template>
