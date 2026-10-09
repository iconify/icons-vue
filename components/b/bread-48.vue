<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kw_wrbbbz.css';
import '../../css/f/ftl4kn5-g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="kw_wrbbbz"/><path class="ftl4kn5-g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:bread-48" /></template>
