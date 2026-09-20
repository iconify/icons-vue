<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/ha17z1bsn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":50,"height":50};
const content = `<path class="ha17z1bsn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="map:fishing-pier" /></template>
