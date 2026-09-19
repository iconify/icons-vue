<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dn5ynfb2y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="dn5ynfb2y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:cheese" /></template>
