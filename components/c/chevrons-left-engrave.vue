<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/p/pomc15b0m.css';
import '../../css/s/s26v07sbu.css';
import '../../css/k/kmdtw6bxj.css';
import '../../css/g/go4z5ccdt.css';
import '../../css/d/dx9i-tzjz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="pomc15b0m wm-k"/><path class="s26v07sbu wm-a"/><path class="kmdtw6bxj wm-shadow"/><path class="go4z5ccdt wm-k"/><path class="dx9i-tzjz wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:chevrons-left-engrave" /></template>
