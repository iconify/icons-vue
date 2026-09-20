<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wlls81mbx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":50,"height":50};
const content = `<path class="wlls81mbx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="map:cafe" /></template>
