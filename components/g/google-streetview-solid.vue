<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nxrry-bew.css';
import '../../css/q/q_k3wsbkz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="nxrry-bew"/><path class="q_k3wsbkz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:google-streetview-solid" /></template>
