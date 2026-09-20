<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rb7_vlbxu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":50,"height":50};
const content = `<path class="rb7_vlbxu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="map:fullscreen" /></template>
