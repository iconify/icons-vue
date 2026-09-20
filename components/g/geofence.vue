<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vju6l6brq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":26,"height":26};
const content = `<path class="vju6l6brq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="wpf:geofence" /></template>
