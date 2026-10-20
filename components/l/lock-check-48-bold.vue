<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/djnf_2eav.css';
import '../../css/g/gxlbmp61p.css';
import '../../css/y/y9mg2tbzu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="djnf_2eav"/><path class="gxlbmp61p"/><path class="y9mg2tbzu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:lock-check-48-bold" /></template>
