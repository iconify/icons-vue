<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/szahujb-p.css';
import '../../css/m/mc4ucsbxd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="szahujb-p"/><path class="mc4ucsbxd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:file-video-20" /></template>
