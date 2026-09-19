<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cvcq89ble.css';
import '../../css/i/iip0rz5nl.css';
import '../../css/o/oqq-bg_3g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<g class="cvcq89ble"><path class="iip0rz5nl"/><path class="oqq-bg_3g"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="catppuccin:dart-generated" /></template>
