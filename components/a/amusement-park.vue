<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oz9x4_4-o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":50,"height":50};
const content = `<path class="oz9x4_4-o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="map:amusement-park" /></template>
