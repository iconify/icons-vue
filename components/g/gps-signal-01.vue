<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jx0p4fbya.css';
import '../../css/l/l_982k12n.css';
import '../../css/o/o4oqigbmb.css';
import '../../css/n/ny9wgu8al.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="l_982k12n"/><path class="o4oqigbmb"/><path class="ny9wgu8al"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:gps-signal-01" /></template>
