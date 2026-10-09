<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/khd4an8mp.css';
import '../../css/k/k98e3f_0o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="khd4an8mp"/><path class="k98e3f_0o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:droplet-48-bold" /></template>
