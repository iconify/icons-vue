<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ivffs4bmd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ivffs4bmd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:flatfish" /></template>
