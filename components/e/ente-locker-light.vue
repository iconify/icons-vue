<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xp1h2bbup.css';
import '../../css/v/vcbva_jjq.css';
import '../../css/y/ya37qbble.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="xp1h2bbup"/><path class="vcbva_jjq"/><path class="ya37qbble"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:ente-locker-light" /></template>
