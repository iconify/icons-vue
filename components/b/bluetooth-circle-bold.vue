<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ojevbbmen.css';
import '../../css/w/w2eatcb7z.css';
import '../../css/x/x10_tqn2d.css';
import '../../css/m/mvm58ibll.css';
import '../../css/q/q7pndkbzr.css';
import '../../css/z/z3u8kpbxh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ojevbbmen"/><path class="w2eatcb7z"/><path class="x10_tqn2d"/><path class="mvm58ibll"/><path class="q7pndkbzr"/><path clip-rule="evenodd" class="z3u8kpbxh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:bluetooth-circle-bold" /></template>
