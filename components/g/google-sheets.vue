<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lews4bcdz.css';
import '../../css/r/rwgs81nbw.css';
import '../../css/o/ogdz0h5td.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="lews4bcdz"/><path class="rwgs81nbw"/><path class="ogdz0h5td"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:google-sheets" /></template>
