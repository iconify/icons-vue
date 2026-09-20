<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r1g812byc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":50,"height":50};
const content = `<path class="r1g812byc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="map:art-gallery" /></template>
