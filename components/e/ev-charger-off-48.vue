<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s6awtztgo.css';
import '../../css/i/i_htz80rx.css';
import '../../css/p/p7kyn66pi.css';
import '../../css/y/y-u291bfo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="s6awtztgo"/><path class="i_htz80rx"/><path class="p7kyn66pi"/><path class="y-u291bfo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:ev-charger-off-48" /></template>
