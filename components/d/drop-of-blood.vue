<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vmwchobpn.css';
import '../../css/e/e8_03wb-a.css';
import '../../css/a/av5-hcwri.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":72,"height":72};
const content = `<path class="vmwchobpn"/><path class="e8_03wb-a"/><path class="av5-hcwri"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="openmoji:drop-of-blood" /></template>
