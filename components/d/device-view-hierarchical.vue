<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pzpx7ib5z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="pzpx7ib5z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:device-view-hierarchical" /></template>
