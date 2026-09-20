<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gv4cxk5nj.css';
import '../../css/k/k09q8my-j.css';
import '../../css/n/nn1z1nbac.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="gv4cxk5nj"/><path class="k09q8my-j"/><path class="nn1z1nbac"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:ksuite-calendar-light" /></template>
