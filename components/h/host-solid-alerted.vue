<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wb-1labtg.css';
import '../../css/h/hfcvhcccg.css';
import '../../css/y/yiybycb-p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<circle class="wb-1labtg"/><path class="hfcvhcccg"/><path class="yiybycb-p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="clarity:host-solid-alerted" /></template>
