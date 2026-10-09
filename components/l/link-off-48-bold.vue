<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kf09_5bop.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="kf09_5bop"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:link-off-48-bold" /></template>
