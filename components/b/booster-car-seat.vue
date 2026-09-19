<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wwvp95byt.css';
import '../../css/s/s7re99ttc.css';
import '../../css/x/xn4himbmb.css';
import '../../css/q/qby2m_svo.css';
import '../../css/v/vtnv7ebqc.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVG3qWRDimI"><g class="wwvp95byt"><path class="s7re99ttc"/><path class="xn4himbmb"/><path class="qby2m_svo"/><path class="vtnv7ebqc"/></g></mask></defs><path mask="url(#SVG3qWRDimI)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-solid:booster-car-seat" /></template>
