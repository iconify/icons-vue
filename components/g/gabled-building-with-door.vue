<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m_hc_3f3z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="m_hc_3f3z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:gabled-building-with-door" /></template>
