<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/th92ccbsb.css';
import '../../css/l/lbnij82qw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="th92ccbsb"/><path class="lbnij82qw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:fhem-dark" /></template>
