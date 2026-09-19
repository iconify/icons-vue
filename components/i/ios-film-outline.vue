<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vtxc1y5_p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="vtxc1y5_p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:ios-film-outline" /></template>
