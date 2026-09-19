<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jx0p4fbya.css';
import '../../css/v/v_mf6nbvh.css';
import '../../css/y/ybsqlk_rx.css';
import '../../css/v/vdc6itbws.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="v_mf6nbvh"/><path class="ybsqlk_rx"/><path class="vdc6itbws"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:cap-straight" /></template>
