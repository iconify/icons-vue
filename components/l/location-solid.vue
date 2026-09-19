<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rh066vywn.css';
import '../../css/c/cobkpuiyr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rh066vywn"/><path clip-rule="evenodd" class="cobkpuiyr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="basil:location-solid" /></template>
