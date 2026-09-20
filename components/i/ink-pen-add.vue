<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dz296k4st.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="dz296k4st"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:ink-pen-add" /></template>
