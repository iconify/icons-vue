<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rz2-bqx6h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="rz2-bqx6h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:android-menu" /></template>
