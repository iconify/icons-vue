<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cmppwob5e.css';
import '../../css/o/o2w8gbcee.css';
import '../../css/v/vc01epbab.css';
import '../../css/n/nre--kigg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":100,"height":100};
const content = `<path class="cmppwob5e"/><path class="o2w8gbcee"/><circle class="vc01epbab"/><path class="nre--kigg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gis:location-man" /></template>
