<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nz_20wbpz.css';
import '../../css/z/z_lk13bab.css';
import '../../css/b/bcbfgeb1t.css';
import '../../css/w/wfqye0b5u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="nz_20wbpz"><path class="z_lk13bab"/><path class="bcbfgeb1t"/><path class="wfqye0b5u"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:income-one" /></template>
