<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/din7kacmm.css';
import '../../css/o/ojbfnibyv.css';
import '../../css/j/jjw_gzn8g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="din7kacmm"/><path class="ojbfnibyv"/><path class="jjw_gzn8g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:ksuite-contacts-dark" /></template>
