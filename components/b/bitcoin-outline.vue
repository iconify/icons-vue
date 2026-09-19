<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h01tyzbfu.css';
import '../../css/d/du5ugufva.css';
import '../../css/x/xdxgcd4hh.css';
import '../../css/u/ui44u43fe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="h01tyzbfu"><path class="du5ugufva"/><path class="xdxgcd4hh"/><path class="ui44u43fe"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bitcoin-icons:bitcoin-outline" /></template>
