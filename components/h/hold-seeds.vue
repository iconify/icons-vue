<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hit3bi0-v.css';
import '../../css/a/ajyf3nzah.css';
import '../../css/s/sqkeg0bva.css';
import '../../css/o/o6j0-0h9i.css';
import '../../css/n/ngj8h-klz.css';
import '../../css/a/a1q2l8btz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="hit3bi0-v"><path class="ajyf3nzah"/><path class="sqkeg0bva"/><circle class="o6j0-0h9i"/><circle class="ngj8h-klz"/><circle class="a1q2l8btz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:hold-seeds" /></template>
