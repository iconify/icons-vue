<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vg2pl9wsr.css';
import '../../css/i/itc5zdbai.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="vg2pl9wsr"/><path class="itc5zdbai"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:ios-refresh-outline" /></template>
