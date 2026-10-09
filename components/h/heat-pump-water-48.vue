<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yph0dvbon.css';
import '../../css/x/xezngbb0n.css';
import '../../css/g/gny111bnl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="yph0dvbon"/><path class="xezngbb0n"/><path class="gny111bnl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:heat-pump-water-48" /></template>
