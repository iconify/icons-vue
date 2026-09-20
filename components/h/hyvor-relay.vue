<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k_1rlqbxe.css';
import '../../css/f/f14y7dbyr.css';
import '../../css/k/ktwj2bcgu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="k_1rlqbxe"/><path class="f14y7dbyr"/><path class="ktwj2bcgu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:hyvor-relay" /></template>
