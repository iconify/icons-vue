<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s17iqx8kn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":50,"height":50};
const content = `<path class="s17iqx8kn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="map:bank" /></template>
