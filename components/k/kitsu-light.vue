<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bp-zmabdk.css';
import '../../css/r/rrklbmuzh.css';
import '../../css/z/zem9k1eun.css';
import '../../css/t/tjho2_-dd.css';
import '../../css/m/mebo6qfse.css';
import '../../css/k/kmsf33cda.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="bp-zmabdk"/><path class="rrklbmuzh"/><path class="zem9k1eun"/><path class="tjho2_-dd"/><path class="mebo6qfse"/><path class="kmsf33cda"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:kitsu-light" /></template>
