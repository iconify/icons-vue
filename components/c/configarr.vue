<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qk3eoukfo.css';
import '../../css/b/bstbd176c.css';
import '../../css/d/ds69pvbkp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="qk3eoukfo"/><path class="bstbd176c"/><path class="ds69pvbkp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:configarr" /></template>
