<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rrd0aac3x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rrd0aac3x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:link-broken2-filled" /></template>
