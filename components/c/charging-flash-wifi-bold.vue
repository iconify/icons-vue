<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rrj-3pr-l.css';
import '../../css/a/alzpy97nw.css';
import '../../css/w/w0xawxcgs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rrj-3pr-l"/><path class="alzpy97nw"/><path class="w0xawxcgs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:charging-flash-wifi-bold" /></template>
