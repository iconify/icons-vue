<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/t/tro8k1dnr.css';
import '../../css/w/wpx6pz7qz.css';
import '../../css/y/y9ujhnbxv.css';
import '../../css/s/soujtab5z.css';
import '../../css/x/xs03ubb6l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="tro8k1dnr wm-k"/><path class="wm-a wpx6pz7qz"/><path class="wm-shadow y9ujhnbxv"/><path class="soujtab5z wm-k"/><path class="wm-a xs03ubb6l"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:inbox-engrave" /></template>
