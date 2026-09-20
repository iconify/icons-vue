<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g2znbebve.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="g2znbebve"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:interface-lighting-light-bulb-on-lighting-light-shine-incandescent-bulb-lights" /></template>
