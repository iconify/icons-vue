<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ie7e9dbhm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="ie7e9dbhm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:heartbeat-bold" /></template>
