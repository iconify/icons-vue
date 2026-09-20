<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gxvcavblc.css';
import '../../css/x/xy40cepxe.css';
import '../../css/e/exoxidbsb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="gxvcavblc"/><path class="xy40cepxe"/><path class="exoxidbsb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:invidious" /></template>
