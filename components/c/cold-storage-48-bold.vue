<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r-50ztbgo.css';
import '../../css/z/zof54ffpy.css';
import '../../css/i/ibk_3obac.css';
import '../../css/u/us_48ubxv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="r-50ztbgo"/><path class="zof54ffpy"/><path class="ibk_3obac"/><path class="us_48ubxv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:cold-storage-48-bold" /></template>
