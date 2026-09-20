<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/olhorlhrj.css';
import '../../css/k/k_zqql6xy.css';
import '../../css/n/nhcbp3bdb.css';
import '../../css/d/d8qet0omc.css';
import '../../css/x/xig01du4t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="olhorlhrj"/><path class="k_zqql6xy"/><path class="nhcbp3bdb"/><path class="d8qet0omc"/><path class="xig01du4t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:ente-photos" /></template>
