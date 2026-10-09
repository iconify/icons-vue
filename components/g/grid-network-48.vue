<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h11c3zb8o.css';
import '../../css/z/z_nkx1xuv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="h11c3zb8o"/><path class="z_nkx1xuv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:grid-network-48" /></template>
