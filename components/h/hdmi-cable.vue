<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z278zvbpd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="z278zvbpd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:hdmi-cable" /></template>
