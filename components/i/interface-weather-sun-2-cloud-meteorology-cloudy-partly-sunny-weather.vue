<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y9tr6bcfx.css';
import '../../css/e/e2k9klemp.css';
import '../../css/m/mwc9s5vvp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<g class="y9tr6bcfx"><path class="e2k9klemp"/><circle class="mwc9s5vvp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:interface-weather-sun-2-cloud-meteorology-cloudy-partly-sunny-weather" /></template>
