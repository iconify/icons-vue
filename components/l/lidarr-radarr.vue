<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a-wkamaxf.css';
import '../../css/s/s6yebsb7h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="a-wkamaxf"/><path class="s6yebsb7h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:lidarr-radarr" /></template>
