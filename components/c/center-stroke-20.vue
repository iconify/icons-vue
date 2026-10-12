<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xdp3vsbnw.css';
import '../../css/f/ftmcmn31x.css';
import '../../css/p/pur2tt30n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="xdp3vsbnw"/><path class="ftmcmn31x"/><path class="pur2tt30n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:center-stroke-20" /></template>
