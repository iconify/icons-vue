<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q3rkygq6d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":50,"height":50};
const content = `<path class="q3rkygq6d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="map:furniture-store" /></template>
