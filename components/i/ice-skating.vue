<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c-yg5n77r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":50,"height":50};
const content = `<path class="c-yg5n77r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="map:ice-skating" /></template>
