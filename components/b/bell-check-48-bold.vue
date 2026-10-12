<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y0__5rb2x.css';
import '../../css/o/ors50g_vw.css';
import '../../css/y/y9mg2tbzu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="y0__5rb2x"/><path class="ors50g_vw"/><path class="y9mg2tbzu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:bell-check-48-bold" /></template>
