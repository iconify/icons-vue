<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/icyfw2p5c.css';
import '../../css/g/g2jzfhoqs.css';
import '../../css/r/rjsh6cbuu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="icyfw2p5c"/><path class="g2jzfhoqs"/><path class="rjsh6cbuu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:cherry-picker-48-bold" /></template>
