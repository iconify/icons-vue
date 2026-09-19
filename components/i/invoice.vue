<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jx0p4fbya.css';
import '../../css/p/pv6pnyb6o.css';
import '../../css/k/kgn4sjj3u.css';
import '../../css/y/yzzxj8nmu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="pv6pnyb6o"/><path class="kgn4sjj3u"/><path class="yzzxj8nmu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:invoice" /></template>
