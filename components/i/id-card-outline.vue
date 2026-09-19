<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gpam7qbjh.css';
import '../../css/h/h0x9monpf.css';
import '../../css/w/wbip20b7n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<rect class="gpam7qbjh"/><path class="h0x9monpf"/><path class="wbip20b7n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="famicons:id-card-outline" /></template>
