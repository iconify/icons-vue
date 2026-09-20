<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l_l_wdbml.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":50,"height":50};
const content = `<path class="l_l_wdbml"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="map:closed-captioning" /></template>
