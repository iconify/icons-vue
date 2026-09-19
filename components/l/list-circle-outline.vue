<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/scd922beo.css';
import '../../css/r/rsyv-4sjc.css';
import '../../css/a/aqo8lubpi.css';
import '../../css/x/x7qr8mbdd.css';
import '../../css/g/gp2g9ybnh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="scd922beo"/><path class="rsyv-4sjc"/><circle class="aqo8lubpi"/><circle class="x7qr8mbdd"/><circle class="gp2g9ybnh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:list-circle-outline" /></template>
