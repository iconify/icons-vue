<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tk7sdpbyr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":50,"height":50};
const content = `<path class="tk7sdpbyr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="map:crosshairs" /></template>
