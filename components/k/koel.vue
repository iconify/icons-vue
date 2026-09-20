<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gfsc7hb7y.css';
import '../../css/r/rr_pm1b7q.css';
import '../../css/u/ucafw4brw.css';
import '../../css/m/m11kaybbv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="gfsc7hb7y"/><path class="rr_pm1b7q"/><path class="ucafw4brw"/><path clip-rule="evenodd" class="m11kaybbv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:koel" /></template>
