<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pggcykugm.css';
import '../../css/s/sfbxtiqsz.css';
import '../../css/o/o8hoowu9h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="pggcykugm"/><path class="sfbxtiqsz"/><path class="o8hoowu9h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:domainmod" /></template>
