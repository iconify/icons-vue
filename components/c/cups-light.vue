<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m_q4zpj6o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="m_q4zpj6o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:cups-light" /></template>
