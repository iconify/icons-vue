<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gjnvknsco.css';
import '../../css/r/rfj-ftw5o.css';
import '../../css/t/tjimueesy.css';
import '../../css/z/za_u7lble.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<linearGradient id="SVGp3x8fc6A" x1="256" x2="256" y1="512" gradientUnits="userSpaceOnUse"><stop offset="0" class="gjnvknsco"/><stop offset=".489" class="rfj-ftw5o"/><stop offset="1" class="tjimueesy"/></linearGradient><path fill="url(#SVGp3x8fc6A)" class="za_u7lble"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:gns3" /></template>
