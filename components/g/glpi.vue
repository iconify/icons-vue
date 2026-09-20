<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i7e_i_bny.css';
import '../../css/w/wrnah39si.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="i7e_i_bny"/><path class="wrnah39si"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:glpi" /></template>
