<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/noo3asbky.css';
import '../../css/c/c9y0u6eai.css';
import '../../css/l/lz_1ujuza.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="noo3asbky"/><path class="c9y0u6eai"/><path class="lz_1ujuza"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fxemoji:clapperboard" /></template>
