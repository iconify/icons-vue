<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tlz4sml2p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="tlz4sml2p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:fuji" /></template>
