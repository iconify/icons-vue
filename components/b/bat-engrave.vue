<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/r/ru8mufbum.css';
import '../../css/p/p93l8_x3q.css';
import '../../css/m/ms5fzqbco.css';
import '../../css/s/sb3ejhbzu.css';
import '../../css/k/kg8q4t51v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="ru8mufbum wm-k"/><path class="p93l8_x3q wm-a"/><path class="ms5fzqbco wm-shadow"/><path class="sb3ejhbzu wm-k"/><path class="kg8q4t51v wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:bat-engrave" /></template>
