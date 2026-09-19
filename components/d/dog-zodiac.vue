<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nz_20wbpz.css';
import '../../css/k/k5pevcbvc.css';
import '../../css/j/jktlcixdp.css';
import '../../css/n/nva12x-3a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="nz_20wbpz"><path class="k5pevcbvc"/><path class="jktlcixdp"/><path class="nva12x-3a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:dog-zodiac" /></template>
