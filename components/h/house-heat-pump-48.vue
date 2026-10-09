<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wvggpac7z.css';
import '../../css/d/ddeq6kb3m.css';
import '../../css/s/sc9dz5b-p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="wvggpac7z"/><path class="ddeq6kb3m"/><path class="sc9dz5b-p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:house-heat-pump-48" /></template>
