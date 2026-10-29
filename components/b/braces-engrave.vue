<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/x/xtt1ysbre.css';
import '../../css/b/blzdo3hjo.css';
import '../../css/x/xyd9cyb9i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="xtt1ysbre"/><path class="blzdo3hjo wm-shadow"/><path class="xyd9cyb9i"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:braces-engrave" /></template>
