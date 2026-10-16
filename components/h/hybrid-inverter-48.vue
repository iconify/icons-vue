<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wgp2dhbyi.css';
import '../../css/e/eeyhvjk3w.css';
import '../../css/b/bzc7nkboy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="wgp2dhbyi"/><path class="eeyhvjk3w"/><path class="bzc7nkboy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:hybrid-inverter-48" /></template>
