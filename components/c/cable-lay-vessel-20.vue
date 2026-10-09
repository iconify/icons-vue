<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/ghdyryixw.css';
import '../../css/n/n_bg76bsh.css';
import '../../css/q/qva2skqil.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="ghdyryixw"/><path class="n_bg76bsh"/><path class="qva2skqil"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:cable-lay-vessel-20" /></template>
