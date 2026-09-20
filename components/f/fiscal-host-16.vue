<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o1hpn4bjj.css';
import '../../css/w/w_0godbis.css';
import '../../css/a/asyhpobbc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="o1hpn4bjj"/><path class="w_0godbis"/><path class="asyhpobbc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:fiscal-host-16" /></template>
