<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rwuetm4pl.css';
import '../../css/c/cyucoabfv.css';
import '../../css/t/tsi3labku.css';
import '../../css/g/gnqkz_bnv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="rwuetm4pl"/><path class="cyucoabfv"/><path class="tsi3labku"/><path class="gnqkz_bnv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:dosvault-dark" /></template>
