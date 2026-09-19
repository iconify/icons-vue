<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q7d-ndb_c.css';
import '../../css/u/uffdfabip.css';
import '../../css/p/pyalxlbvl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<circle class="q7d-ndb_c"/><circle class="uffdfabip"/><circle class="pyalxlbvl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="famicons:ellipsis-horizontal" /></template>
