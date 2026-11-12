<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/phg1s7mys.css';
import '../../css/g/gr0vkeb_g.css';
import '../../css/p/pd-439hvt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="phg1s7mys"/><path class="gr0vkeb_g"/><path class="pd-439hvt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:ente-locker-dark" /></template>
