<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z_nhushwe.css';
import '../../css/d/dvyctl1bu.css';
import '../../css/w/wvf8eitqm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="z_nhushwe"/><path class="dvyctl1bu"/><path class="wvf8eitqm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:flight-roster" /></template>
