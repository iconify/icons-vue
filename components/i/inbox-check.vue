<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jx0p4fbya.css';
import '../../css/h/hxo2p_vlt.css';
import '../../css/x/xknbt5ism.css';
import '../../css/a/ak7meacck.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="hxo2p_vlt"/><path class="xknbt5ism"/><path class="ak7meacck"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:inbox-check" /></template>
