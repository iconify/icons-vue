<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/c/c8mmccbpe.css';
import '../../css/z/z7u4j99sm.css';
import '../../css/b/b4d1e6bie.css';
import '../../css/w/wcpe8eb7b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="c8mmccbpe wm-k"/><path class="wm-shadow z7u4j99sm"/><path class="b4d1e6bie wm-k"/><path class="wcpe8eb7b wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:car-front-engrave" /></template>
