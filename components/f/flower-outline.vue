<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/ws3dbbcgn.css';
import '../../css/p/p1ijl2b0l.css';
import '../../css/y/yo8uw-b3d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ws3dbbcgn"/><path class="p1ijl2b0l"/><circle class="yo8uw-b3d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="famicons:flower-outline" /></template>
