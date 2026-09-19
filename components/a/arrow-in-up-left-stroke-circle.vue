<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/ns3pdubbz.css';
import '../../css/v/vnep0m7rs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ns3pdubbz"/><path class="vnep0m7rs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:arrow-in-up-left-stroke-circle" /></template>
