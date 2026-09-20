<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n1br3obmn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":50,"height":50};
const content = `<path class="n1br3obmn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="map:boat-ramp" /></template>
