<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h-71aubjb.css';
import '../../css/s/s6yebsb7h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="h-71aubjb"/><path class="s6yebsb7h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:lidarr-radarr-light" /></template>
