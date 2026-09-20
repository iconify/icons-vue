<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bscwe4z-x.css';
import '../../css/i/iuqenpiuh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="bscwe4z-x"/><path class="iuqenpiuh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-pixel:internet-network-wifi-monitor" /></template>
