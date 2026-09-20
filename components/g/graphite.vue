<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ixba4jbjx.css';
import '../../css/n/nfuq28b1b.css';
import '../../css/r/rwvtvxb9z.css';
import '../../css/p/p63a8fbod.css';
import '../../css/e/eto7q3jmi.css';
import '../../css/q/qwqkqda_t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ixba4jbjx"/><path class="nfuq28b1b"/><path class="rwvtvxb9z"/><path class="p63a8fbod"/><path class="eto7q3jmi"/><path class="qwqkqda_t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:graphite" /></template>
